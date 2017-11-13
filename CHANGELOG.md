## 1.2.0 (unreleased)

## 1.1.16 (November 13, 2017)

IMPROVEMENTS:

  * foormark/vpc/connection: modify deleting vswitch timeout to 120 ([#51](https://github.com/alibaba/footmark/pull/51))

## 1.1.15 (November 13, 2017)

IMPROVEMENTS:

  * foormark/ecs/instance: improve eip_address ([#51](https://github.com/alibaba/footmark/pull/51))
  * foormark/vpc/connection: modify and improve eip methods ([#51](https://github.com/alibaba/footmark/pull/51))
  * foormark/vpc/eip: modify and improve eip methods ([#51](https://github.com/alibaba/footmark/pull/51))
  * foormark/vpc/config.py: modify default interval ([#51](https://github.com/alibaba/footmark/pull/51))

## 1.1.14 (November 6, 2017)

IMPROVEMENTS:

  * foormark/ecs/connection: add key_name and userdata ([#48](https://github.com/alibaba/footmark/pull/48))
  * foormark/ecs/connection: improve retry when delete instance ([#48](https://github.com/alibaba/footmark/pull/48))


## 1.1.13 (November 2, 2017)

IMPROVEMENTS:

  * foormark/ecs/connection: add client-token for disk and security creating ([#47](https://github.com/alibaba/footmark/pull/47))
  * foormark/vpc/connection: add client-token for vpc and vswitch creating ([#47](https://github.com/alibaba/footmark/pull/47))
  * foormark/slb/connection: add client-token for load balancer creating ([#47](https://github.com/alibaba/footmark/pull/47))
  * foormark/rds/connection: add client-token for rds instance creating ([#47](https://github.com/alibaba/footmark/pull/47))


## 1.1.12 (November 2, 2017)

IMPROVEMENTS:

  * foormark/ecs/connection: improve get_all_instances ([#46](https://github.com/alibaba/footmark/pull/46))
  * foormark/ecs/connection: check max bandwidth out before creating instances ([#50](https://github.com/alibaba/footmark/pull/46))
  * foormark/ecs/instance: improve ip address attribute ([#46](https://github.com/alibaba/footmark/pull/50))

BUG FIXES:

  * footmark/connection: fix InvalidSignature by adding client-token ([#46](https://github.com/alibaba/footmark/pull/46))

## 1.1.11

  * improve ECS, OSS, RDS, SLB and VPC module
