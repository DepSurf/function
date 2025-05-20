# Function: <code>dev_remove_pack</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dev_remove_pack(struct packet_type *pt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81716480)
Location: net/core/dev.c:450
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff81716480-ffffffff81716495: dev_remove_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dev_remove_pack(struct packet_type *pt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8177e360)
Location: net/core/dev.c:454
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_release
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
```
**Symbols:**

```
ffffffff8177e360-ffffffff8177e375: dev_remove_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dev_remove_pack(struct packet_type *pt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817abb60)
Location: net/core/dev.c:453
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
```
**Symbols:**

```
ffffffff817abb60-ffffffff817abb75: dev_remove_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dev_remove_pack(struct packet_type *pt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817ca0f0)
Location: net/core/dev.c:460
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
```
**Symbols:**

```
ffffffff817ca0f0-ffffffff817ca105: dev_remove_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dev_remove_pack(struct packet_type *pt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81843a10)
Location: net/core/dev.c:463
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
```
**Symbols:**

```
ffffffff81843a10-ffffffff81843a25: dev_remove_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dev_remove_pack(struct packet_type *pt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81891570)
Location: net/core/dev.c:463
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_init
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
```
**Symbols:**

```
ffffffff81891570-ffffffff81891585: dev_remove_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dev_remove_pack(struct packet_type *pt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b2160)
Location: net/core/dev.c:465
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_init
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
```
**Symbols:**

```
ffffffff818b2160-ffffffff818b2175: dev_remove_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dev_remove_pack(struct packet_type *pt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818fe930)
Location: net/core/dev.c:461
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_init
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
```
**Symbols:**

```
ffffffff818fe930-ffffffff818fe945: dev_remove_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dev_remove_pack(struct packet_type *pt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81930c70)
Location: net/core/dev.c:379
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_init
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
```
**Symbols:**

```
ffffffff81930c70-ffffffff81930c85: dev_remove_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dev_remove_pack(struct packet_type *pt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a048a0)
Location: net/core/dev.c:585
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_init
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
```
**Symbols:**

```
ffffffff81a048a0-ffffffff81a048ca: dev_remove_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dev_remove_pack(struct packet_type *pt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a04f90)
Location: net/core/dev.c:588
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_init
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
```
**Symbols:**

```
ffffffff81a04f90-ffffffff81a04fba: dev_remove_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dev_remove_pack(struct packet_type *pt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819ecad0)
Location: net/core/dev.c:590
Inline: False
Direct callers:
  - net/core/selftests.c:__net_test_loopback
  - net/ipv6/af_inet6.c:inet6_init
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
```
**Symbols:**

```
ffffffff819ecad0-ffffffff819ecafa: dev_remove_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dev_remove_pack(struct packet_type *pt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a9db10)
Location: net/core/dev.c:592
Inline: False
Direct callers:
  - net/core/selftests.c:__net_test_loopback
  - net/ipv6/af_inet6.c:inet6_init
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
```
**Symbols:**

```
ffffffff81a9db10-ffffffff81a9db3a: dev_remove_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dev_remove_pack(struct packet_type *pt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c12380)
Location: net/core/dev.c:613
Inline: False
Direct callers:
  - net/core/selftests.c:__net_test_loopback
  - net/ipv6/af_inet6.c:inet6_init
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
  - net/mctp/route.c:mctp_routes_exit
```
**Symbols:**

```
ffffffff81c12380-ffffffff81c123ba: dev_remove_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dev_remove_pack(struct packet_type *pt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc27f0)
Location: net/core/dev.c:613
Inline: False
Direct callers:
  - net/core/selftests.c:__net_test_loopback
  - net/ipv6/af_inet6.c:inet6_init
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
  - net/mctp/route.c:mctp_routes_exit
```
**Symbols:**

```
ffffffff81dc27f0-ffffffff81dc282a: dev_remove_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dev_remove_pack(struct packet_type *pt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e31c00)
Location: net/core/dev.c:611
Inline: False
Direct callers:
  - net/core/selftests.c:__net_test_loopback
  - net/ipv6/af_inet6.c:inet6_init
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
  - net/mctp/route.c:mctp_routes_exit
```
**Symbols:**

```
ffffffff81e31c00-ffffffff81e31c3a: dev_remove_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dev_remove_pack(struct packet_type *pt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ef0080)
Location: net/core/dev.c:628
Inline: False
Direct callers:
  - net/core/selftests.c:__net_test_loopback
  - net/ipv6/af_inet6.c:inet6_init
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
  - net/mctp/route.c:mctp_routes_exit
```
**Symbols:**

```
ffffffff81ef0080-ffffffff81ef00ba: dev_remove_pack (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void dev_remove_pack(struct packet_type *pt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bcd5b0)
Location: net/core/dev.c:379
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_init
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
```
**Symbols:**

```
ffff800010bcd5b0-ffff800010bcd5e0: dev_remove_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dev_remove_pack(struct packet_type *pt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce51d4)
Location: net/core/dev.c:379
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_init
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
```
**Symbols:**

```
c0ce51d4-c0ce51f4: dev_remove_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dev_remove_pack(struct packet_type *pt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca5b60)
Location: net/core/dev.c:379
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_init
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
```
**Symbols:**

```
c000000000ca5b60-c000000000ca5b90: dev_remove_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dev_remove_pack(struct packet_type *pt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe000758718)
Location: net/core/dev.c:379
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_init
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
```
**Symbols:**

```
ffffffe000758718-ffffffe00075874a: dev_remove_pack (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void dev_remove_pack(struct packet_type *pt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d0c70)
Location: net/core/dev.c:379
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_init
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
```
**Symbols:**

```
ffffffff818d0c70-ffffffff818d0c85: dev_remove_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dev_remove_pack(struct packet_type *pt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188ab50)
Location: net/core/dev.c:379
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_init
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
```
**Symbols:**

```
ffffffff8188ab50-ffffffff8188ab65: dev_remove_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dev_remove_pack(struct packet_type *pt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81921c70)
Location: net/core/dev.c:379
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_init
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
```
**Symbols:**

```
ffffffff81921c70-ffffffff81921c85: dev_remove_pack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dev_remove_pack(struct packet_type *pt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8193eea0)
Location: net/core/dev.c:379
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_init
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
```
**Symbols:**

```
ffffffff8193eea0-ffffffff8193eeb5: dev_remove_pack (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
