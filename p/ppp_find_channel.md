# Function: <code>ppp_find_channel</code>

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
In drivers/net/ppp/ppp_generic.c (ffffffff815f885b)
Location: drivers/net/ppp/ppp_generic.c:2888
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
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
In drivers/net/ppp/ppp_generic.c (ffffffff8165883f)
Location: drivers/net/ppp/ppp_generic.c:3043
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
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
In drivers/net/ppp/ppp_generic.c (ffffffff816865c1)
Location: drivers/net/ppp/ppp_generic.c:3082
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
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
In drivers/net/ppp/ppp_generic.c (ffffffff8169bb4e)
Location: drivers/net/ppp/ppp_generic.c:3097
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
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
In drivers/net/ppp/ppp_generic.c (ffffffff81706b58)
Location: drivers/net/ppp/ppp_generic.c:3124
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
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
In drivers/net/ppp/ppp_generic.c (ffffffff81745517)
Location: drivers/net/ppp/ppp_generic.c:3107
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
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
In drivers/net/ppp/ppp_generic.c (ffffffff81769607)
Location: drivers/net/ppp/ppp_generic.c:3155
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
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
In drivers/net/ppp/ppp_generic.c (ffffffff817a7488)
Location: drivers/net/ppp/ppp_generic.c:3151
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
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
In drivers/net/ppp/ppp_generic.c (ffffffff817caef8)
Location: drivers/net/ppp/ppp_generic.c:3151
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
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
In drivers/net/ppp/ppp_generic.c (ffffffff81893da2)
Location: drivers/net/ppp/ppp_generic.c:3235
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct channel *ppp_find_channel(struct ppp_net *pn, int unit);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff8189f740)
Location: drivers/net/ppp/ppp_generic.c:3386
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
**Symbols:**

```
ffffffff8189f740-ffffffff8189f7bf: ppp_find_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct channel *ppp_find_channel(struct ppp_net *pn, int unit);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff818821d0)
Location: drivers/net/ppp/ppp_generic.c:3419
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
**Symbols:**

```
ffffffff818821d0-ffffffff8188224f: ppp_find_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct channel *ppp_find_channel(struct ppp_net *pn, int unit);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81913b70)
Location: drivers/net/ppp/ppp_generic.c:3424
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
**Symbols:**

```
ffffffff81913b70-ffffffff81913bef: ppp_find_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct channel *ppp_find_channel(struct ppp_net *pn, int unit);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81a69030)
Location: drivers/net/ppp/ppp_generic.c:3425
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
**Symbols:**

```
ffffffff81a69030-ffffffff81a690dc: ppp_find_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct channel *ppp_find_channel(struct ppp_net *pn, int unit);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfba10)
Location: drivers/net/ppp/ppp_generic.c:3427
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
**Symbols:**

```
ffffffff81bfba10-ffffffff81bfbabc: ppp_find_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct channel *ppp_find_channel(struct ppp_net *pn, int unit);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81c60fa0)
Location: drivers/net/ppp/ppp_generic.c:3427
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
**Symbols:**

```
ffffffff81c60fa0-ffffffff81c6104c: ppp_find_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct channel *ppp_find_channel(struct ppp_net *pn, int unit);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81d17970)
Location: drivers/net/ppp/ppp_generic.c:3427
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
**Symbols:**

```
ffffffff81d17970-ffffffff81d17a1c: ppp_find_channel (STB_LOCAL)
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
In drivers/net/ppp/ppp_generic.c (ffff800010a02900)
Location: drivers/net/ppp/ppp_generic.c:3151
Inline: True
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
In drivers/net/ppp/ppp_generic.c (c0adf7d4)
Location: drivers/net/ppp/ppp_generic.c:3151
Inline: True
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
In drivers/net/ppp/ppp_generic.c (c000000000aab248)
Location: drivers/net/ppp/ppp_generic.c:3151
Inline: True
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
In drivers/net/ppp/ppp_generic.c (ffffffe00062f0ae)
Location: drivers/net/ppp/ppp_generic.c:3151
Inline: True
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
In drivers/net/ppp/ppp_generic.c (ffffffff8178f9d8)
Location: drivers/net/ppp/ppp_generic.c:3151
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
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
In drivers/net/ppp/ppp_generic.c (ffffffff817787a8)
Location: drivers/net/ppp/ppp_generic.c:3151
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
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
In drivers/net/ppp/ppp_generic.c (ffffffff817bfd78)
Location: drivers/net/ppp/ppp_generic.c:3151
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
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
In drivers/net/ppp/ppp_generic.c (ffffffff817da020)
Location: drivers/net/ppp/ppp_generic.c:3151
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
