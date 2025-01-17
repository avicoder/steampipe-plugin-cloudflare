## v0.8.0 [2023-07-06]

_What's new?_

- New tables added
  - [cloudflare_r2_bucket](https://hub.steampipe.io/plugins/turbot/cloudflare/tables/cloudflare_r2_bucket) ([#43](https://github.com/turbot/steampipe-plugin-cloudflare/pull/43))
  - [cloudflare_r2_object_data](https://hub.steampipe.io/plugins/turbot/cloudflare/tables/cloudflare_r2_object_data) ([#43](https://github.com/turbot/steampipe-plugin-cloudflare/pull/43))
  - [cloudflare_r2_object](https://hub.steampipe.io/plugins/turbot/cloudflare/tables/cloudflare_r2_object) ([#43](https://github.com/turbot/steampipe-plugin-cloudflare/pull/43))
- Added `access_key` and `secret_key` config arguments to query `cloudflare_r2_*` tables. ([#43](https://github.com/turbot/steampipe-plugin-cloudflare/pull/43))

## v0.7.0 [2023-06-08]

_What's new?_

- New tables added
  - [cloudflare_user_audit_log](https://hub.steampipe.io/plugins/turbot/cloudflare/tables/cloudflare_user_audit_log) ([#41](https://github.com/turbot/steampipe-plugin-cloudflare/pull/41))

## v0.6.0 [2023-03-22]

_Bug fixes_

- Fixed pagination in `cloudflare_account_member` table. ([#39](https://github.com/turbot/steampipe-plugin-cloudflare/pull/39))

_Dependencies_

- Recompiled plugin with [steampipe-plugin-sdk v5.3.0](https://github.com/turbot/steampipe-plugin-sdk/blob/main/CHANGELOG.md#v530-2023-03-16) which includes fixes for query cache pending item mechanism and aggregator connections not working for dynamic tables. ([#48](https://github.com/turbot/steampipe-plugin-cloudflare/pull/48))

## v0.5.0 [2022-09-28]

_Dependencies_

- Recompiled plugin with [steampipe-plugin-sdk v4.1.7](https://github.com/turbot/steampipe-plugin-sdk/blob/main/CHANGELOG.md#v417-2022-09-08) which includes several caching and memory management improvements. ([#37](https://github.com/turbot/steampipe-plugin-cloudflare/pull/37))
- Recompiled plugin with Go version `1.19`. ([#37](https://github.com/turbot/steampipe-plugin-cloudflare/pull/37))


## v0.4.0 [2022-04-27]

_Enhancements_

- Recompiled plugin with [steampipe-plugin-sdk v3.1.0](https://github.com/turbot/steampipe-plugin-sdk/blob/main/CHANGELOG.md#v310--2022-03-30) and Go version `1.18`. ([#30](https://github.com/turbot/steampipe-plugin-cloudflare/pull/30))
- Added support for native Linux ARM and Mac M1 builds. ([#29](https://github.com/turbot/steampipe-plugin-cloudflare/pull/29))

## v0.3.0 [2021-12-22]

_What's new?_

- New tables added
  - [cloudflare_account_member](https://hub.steampipe.io/plugins/turbot/cloudflare/tables/cloudflare_account_member) ([#4](https://github.com/turbot/steampipe-plugin-cloudflare/pull/4))

## v0.2.0 [2021-12-08]

_What's new?_

- New tables added
  - [cloudflare_access_application](https://hub.steampipe.io/plugins/turbot/cloudflare/tables/cloudflare_access_application) ([#19](https://github.com/turbot/steampipe-plugin-cloudflare/pull/19))
  - [cloudflare_access_group](https://hub.steampipe.io/plugins/turbot/cloudflare/tables/cloudflare_access_group) ([#19](https://github.com/turbot/steampipe-plugin-cloudflare/pull/19))
  - [cloudflare_access_policy](https://hub.steampipe.io/plugins/turbot/cloudflare/tables/cloudflare_access_policy) ([#19](https://github.com/turbot/steampipe-plugin-cloudflare/pull/19))
  - [cloudflare_load_balancer](https://hub.steampipe.io/plugins/turbot/cloudflare/tables/cloudflare_load_balancer) ([#19](https://github.com/turbot/steampipe-plugin-cloudflare/pull/19))
  - [cloudflare_load_balancer_monitor](https://hub.steampipe.io/plugins/turbot/cloudflare/tables/cloudflare_load_balancer_monitor) ([#19](https://github.com/turbot/steampipe-plugin-cloudflare/pull/19))
  - [cloudflare_load_balancer_pool](https://hub.steampipe.io/plugins/turbot/cloudflare/tables/cloudflare_load_balancer_pool) ([#19](https://github.com/turbot/steampipe-plugin-cloudflare/pull/19))
  - [cloudflare_worker_route](https://hub.steampipe.io/plugins/turbot/cloudflare/tables/cloudflare_worker_route) ([#19](https://github.com/turbot/steampipe-plugin-cloudflare/pull/19))

_Enhancements_

- `README.md` and `docs/index.md` files now have updated Slack channel links

## v0.1.0 [2021-11-23]

_Enhancements_

- Recompiled plugin with Go version 1.17 ([#23](https://github.com/turbot/steampipe-plugin-cloudflare/pull/23))
- Recompiled plugin with [steampipe-plugin-sdk v1.8.2](https://github.com/turbot/steampipe-plugin-sdk/blob/main/CHANGELOG.md#v182--2021-11-22) ([#22](https://github.com/turbot/steampipe-plugin-cloudflare/pull/22))

## v0.0.3 [2021-10-04]

_Enhancements_

- Updated the README file as per the latest format ([#18](https://github.com/turbot/steampipe-plugin-cloudflare/pull/18))

_Bug fixes_
- Fixed the `cloudflare_zone` table to include the missing `dnssec` and `settings` columns ([#17](https://github.com/turbot/steampipe-plugin-cloudflare/pull/17))

## v0.0.2 [2021-07-02]

_What's new?_

- New tables added
  - [cloudflare_account_role](https://hub.steampipe.io/plugins/turbot/cloudflare/tables/cloudflare_account_role) ([#6](https://github.com/turbot/steampipe-plugin-cloudflare/pull/6))
  - [cloudflare_firewall_rule](https://hub.steampipe.io/plugins/turbot/cloudflare/tables/cloudflare_firewall_rule) ([#8](https://github.com/turbot/steampipe-plugin-cloudflare/pull/8))
  - [cloudflare_page_rule](https://hub.steampipe.io/plugins/turbot/cloudflare/tables/cloudflare_page_rule) ([#10](https://github.com/turbot/steampipe-plugin-cloudflare/pull/10))

_Enhancements_

- Updated plugin category from `networking` to `internet`
- Updated plugin license to Apache 2.0 per [turbot/steampipe#488](https://github.com/turbot/steampipe/issues/488)

## v0.0.1 [2021-03-11]

_What's new?_

- Initial release with tables for accounts, API tokens, DNS records, users, and zones.
