# Function: <code>tun_put_user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff815ee288)
Location: drivers/net/tun.c:1287
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8164e7e2)
Location: drivers/net/tun.c:1343
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff816804f2)
Location: drivers/net/tun.c:1336
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff816958a8)
Location: drivers/net/tun.c:1373
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817003f7)
Location: drivers/net/tun.c:1820
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8173fce2)
Location: drivers/net/tun.c:2051
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81763d02)
Location: drivers/net/tun.c:2069
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817a1a9a)
Location: drivers/net/tun.c:2064
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817c276a)
Location: drivers/net/tun.c:2068
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (0)
Location: drivers/net/tun.c:2043
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_do_read
```
**Symbols:**

```
ffffffff8188a990-ffffffff8188ac7a: tun_put_user.constprop.0 (STB_LOCAL)
ffffffff8189092c-ffffffff81890988: tun_put_user.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (0)
Location: drivers/net/tun.c:1969
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_do_read
```
**Symbols:**

```
ffffffff81898b90-ffffffff81898e86: tun_put_user.constprop.0 (STB_LOCAL)
ffffffff81c1959f-ffffffff81c195fb: tun_put_user.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (0)
Location: drivers/net/tun.c:1974
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_do_read
```
**Symbols:**

```
ffffffff8187b2d0-ffffffff8187b5a1: tun_put_user.constprop.0 (STB_LOCAL)
ffffffff81c0b3fb-ffffffff81c0b456: tun_put_user.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (0)
Location: drivers/net/tun.c:2030
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_do_read
```
**Symbols:**

```
ffffffff8190c680-ffffffff8190c951: tun_put_user.constprop.0 (STB_LOCAL)
ffffffff81d1097c-ffffffff81d109d7: tun_put_user.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (0)
Location: drivers/net/tun.c:2062
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_do_read
```
**Symbols:**

```
ffffffff81a60290-ffffffff81a60589: tun_put_user.constprop.0 (STB_LOCAL)
ffffffff81edb732-ffffffff81edb78d: tun_put_user.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff81beb920)
Location: drivers/net/tun.c:2066
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_do_read
```
**Symbols:**

```
ffffffff81beb920-ffffffff81bebc6d: tun_put_user.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff81c43dd0)
Location: drivers/net/tun.c:2080
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_do_read
```
**Symbols:**

```
ffffffff81c43dd0-ffffffff81c44112: tun_put_user.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff81cf9690)
Location: drivers/net/tun.c:2092
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_do_read
```
**Symbols:**

```
ffffffff81cf9690-ffffffff81cf99d2: tun_put_user.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffff8000109dd278)
Location: drivers/net/tun.c:2068
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (c0ac5a28)
Location: drivers/net/tun.c:2068
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (c000000000aa38d0)
Location: drivers/net/tun.c:2068
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffe0006284da)
Location: drivers/net/tun.c:2068
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8178723a)
Location: drivers/net/tun.c:2068
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81766b8a)
Location: drivers/net/tun.c:2068
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817b75ea)
Location: drivers/net/tun.c:2068
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817d1c4d)
Location: drivers/net/tun.c:2068
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_do_read
```
</details>
</li>
</ul>

## Differences
