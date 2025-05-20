# Function: <code>tun_dst_unclone</code>

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
In net/core/dev.c (ffffffff817141d2)
Location: include/net/dst_metadata.h:81
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
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
In net/core/dev.c (ffffffff8177bfe2)
Location: include/net/dst_metadata.h:82
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
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
In net/core/dev.c (ffffffff817a9772)
Location: include/net/dst_metadata.h:82
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
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
In net/core/dev.c (ffffffff817c7d60)
Location: include/net/dst_metadata.h:105
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
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
In net/core/dev.c (ffffffff818418f0)
Location: include/net/dst_metadata.h:108
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
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
In net/core/dev.c (ffffffff8188bd83)
Location: include/net/dst_metadata.h:108
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
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
In net/core/dev.c (ffffffff818acf63)
Location: include/net/dst_metadata.h:108
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
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
In net/core/dev.c (ffffffff818f8802)
Location: include/net/dst_metadata.h:108
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
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
In net/core/dev.c (ffffffff8192a9a2)
Location: include/net/dst_metadata.h:108
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
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
In net/core/dev.c (ffffffff819fe6d2)
Location: include/net/dst_metadata.h:108
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
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
In net/core/dev.c (ffffffff819fe2d2)
Location: include/net/dst_metadata.h:108
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
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
In net/core/dev.c (ffffffff819e4b42)
Location: include/net/dst_metadata.h:110
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
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
In net/core/dev.c (ffffffff81a95530)
Location: include/net/dst_metadata.h:110
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
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
In net/core/dev.c (ffffffff81c0bc92)
Location: include/net/dst_metadata.h:110
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct metadata_dst *tun_dst_unclone(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: include/net/dst_metadata.h:152
Inline: False
Direct callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
**Symbols:**

```
ffffffff81dbd6c0-ffffffff81dbd836: tun_dst_unclone (STB_LOCAL)
ffffffff820ab119-ffffffff820ab13c: tun_dst_unclone.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct metadata_dst *tun_dst_unclone(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: include/net/dst_metadata.h:152
Inline: False
Direct callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
**Symbols:**

```
ffffffff81e2df00-ffffffff81e2e082: tun_dst_unclone (STB_LOCAL)
ffffffff8212c7c2-ffffffff8212c7e5: tun_dst_unclone.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct metadata_dst *tun_dst_unclone(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: include/net/dst_metadata.h:152
Inline: False
Direct callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
**Symbols:**

```
ffffffff81eec2e0-ffffffff81eec462: tun_dst_unclone (STB_LOCAL)
ffffffff8220e4ec-ffffffff8220e50f: tun_dst_unclone.cold (STB_LOCAL)
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
In net/core/dev.c (ffff800010bcdf38)
Location: include/net/dst_metadata.h:108
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
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
In net/core/dev.c (c0ce79f8)
Location: include/net/dst_metadata.h:108
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
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
In net/core/dev.c (c000000000ca2564)
Location: include/net/dst_metadata.h:108
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
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
In net/core/dev.c (ffffffe00075384c)
Location: include/net/dst_metadata.h:108
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
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
In net/core/dev.c (ffffffff818ca9a2)
Location: include/net/dst_metadata.h:108
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
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
In net/core/dev.c (ffffffff818848e2)
Location: include/net/dst_metadata.h:108
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
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
In net/core/dev.c (ffffffff8191b9a2)
Location: include/net/dst_metadata.h:108
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
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
In net/core/dev.c (ffffffff8193ccf2)
Location: include/net/dst_metadata.h:108
Inline: True
Inline callers:
  - net/core/dev.c:dev_fill_metadata_dst
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
