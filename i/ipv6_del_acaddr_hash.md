# Function: <code>ipv6_del_acaddr_hash</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ipv6_del_acaddr_hash(struct ifacaddr6 *aca);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/anycast.c (ffffffff81993e40)
Location: net/ipv6/anycast.c:230
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
```
**Symbols:**

```
ffffffff81993e40-ffffffff81993e8b: ipv6_del_acaddr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ipv6_del_acaddr_hash(struct ifacaddr6 *aca);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/anycast.c (ffffffff819ff8d0)
Location: net/ipv6/anycast.c:226
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
```
**Symbols:**

```
ffffffff819ff8d0-ffffffff819ff91b: ipv6_del_acaddr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ipv6_del_acaddr_hash(struct ifacaddr6 *aca);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/anycast.c (ffffffff81a364b0)
Location: net/ipv6/anycast.c:226
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
```
**Symbols:**

```
ffffffff81a364b0-ffffffff81a364fb: ipv6_del_acaddr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/anycast.c (ffffffff81b2c00d)
Location: net/ipv6/anycast.c:233
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/anycast.c (ffffffff81b3aa2d)
Location: net/ipv6/anycast.c:233
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/anycast.c (ffffffff81b2870d)
Location: net/ipv6/anycast.c:233
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/anycast.c (ffffffff81bee6cd)
Location: net/ipv6/anycast.c:233
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/anycast.c (ffffffff81d86c2e)
Location: net/ipv6/anycast.c:233
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/anycast.c (ffffffff81f547de)
Location: net/ipv6/anycast.c:233
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/anycast.c (ffffffff81fb41ee)
Location: net/ipv6/anycast.c:233
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/anycast.c (ffffffff82081a9e)
Location: net/ipv6/anycast.c:233
Inline: True
Inline callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
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
void ipv6_del_acaddr_hash(struct ifacaddr6 *aca);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/anycast.c (ffff800010cf6fd8)
Location: net/ipv6/anycast.c:226
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
```
**Symbols:**

```
ffff800010cf6fd8-ffff800010cf7074: ipv6_del_acaddr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ipv6_del_acaddr_hash(struct ifacaddr6 *aca);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/anycast.c (c0dfd4e0)
Location: net/ipv6/anycast.c:226
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
```
**Symbols:**

```
c0dfd4e0-c0dfd54c: ipv6_del_acaddr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ipv6_del_acaddr_hash(struct ifacaddr6 *aca);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/anycast.c (c000000000e1d840)
Location: net/ipv6/anycast.c:226
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
```
**Symbols:**

```
c000000000e1d840-c000000000e1d91c: ipv6_del_acaddr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ipv6_del_acaddr_hash(struct ifacaddr6 *aca);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/anycast.c (ffffffe0008424e0)
Location: net/ipv6/anycast.c:226
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
```
**Symbols:**

```
ffffffe0008424e0-ffffffe000842564: ipv6_del_acaddr_hash (STB_LOCAL)
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
void ipv6_del_acaddr_hash(struct ifacaddr6 *aca);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/anycast.c (ffffffff819d5b40)
Location: net/ipv6/anycast.c:226
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
```
**Symbols:**

```
ffffffff819d5b40-ffffffff819d5b8b: ipv6_del_acaddr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ipv6_del_acaddr_hash(struct ifacaddr6 *aca);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/anycast.c (ffffffff81992900)
Location: net/ipv6/anycast.c:226
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
```
**Symbols:**

```
ffffffff81992900-ffffffff8199294b: ipv6_del_acaddr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ipv6_del_acaddr_hash(struct ifacaddr6 *aca);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/anycast.c (ffffffff81a405c0)
Location: net/ipv6/anycast.c:226
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
```
**Symbols:**

```
ffffffff81a405c0-ffffffff81a4060b: ipv6_del_acaddr_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ipv6_del_acaddr_hash(struct ifacaddr6 *aca);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/anycast.c (ffffffff81a4bf80)
Location: net/ipv6/anycast.c:226
Inline: False
Direct callers:
  - net/ipv6/anycast.c:ipv6_ac_destroy_dev
  - net/ipv6/anycast.c:__ipv6_dev_ac_dec
```
**Symbols:**

```
ffffffff81a4bf80-ffffffff81a4bfc9: ipv6_del_acaddr_hash (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
