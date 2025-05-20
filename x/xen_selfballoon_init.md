# Function: <code>xen_selfballoon_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int xen_selfballoon_init(bool use_selfballooning, bool use_frontswap_selfshrink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xen-selfballoon.c (ffffffff814d35e0)
Location: drivers/xen/xen-selfballoon.c:527
Inline: False
```
**Symbols:**

```
ffffffff814d35e0-ffffffff814d36ba: xen_selfballoon_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int xen_selfballoon_init(bool use_selfballooning, bool use_frontswap_selfshrink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xen-selfballoon.c (ffffffff81524300)
Location: drivers/xen/xen-selfballoon.c:526
Inline: False
```
**Symbols:**

```
ffffffff81524300-ffffffff815243e2: xen_selfballoon_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int xen_selfballoon_init(bool use_selfballooning, bool use_frontswap_selfshrink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xen-selfballoon.c (ffffffff815507c0)
Location: drivers/xen/xen-selfballoon.c:526
Inline: False
```
**Symbols:**

```
ffffffff815507c0-ffffffff815508a2: xen_selfballoon_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xen_selfballoon_init(bool use_selfballooning, bool use_frontswap_selfshrink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xen-selfballoon.c (ffffffff81564f10)
Location: drivers/xen/xen-selfballoon.c:526
Inline: False
```
**Symbols:**

```
ffffffff81564f10-ffffffff81564fee: xen_selfballoon_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xen_selfballoon_init(bool use_selfballooning, bool use_frontswap_selfshrink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xen-selfballoon.c (ffffffff815c90a0)
Location: drivers/xen/xen-selfballoon.c:527
Inline: False
```
**Symbols:**

```
ffffffff815c90a0-ffffffff815c917e: xen_selfballoon_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int xen_selfballoon_init(bool use_selfballooning, bool use_frontswap_selfshrink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xen-selfballoon.c (0)
Location: drivers/xen/xen-selfballoon.c:527
Inline: False
```
**Symbols:**

```
ffffffff81601984-ffffffff81601a14: xen_selfballoon_init.cold.0 (STB_LOCAL)
ffffffff81601930-ffffffff81601984: xen_selfballoon_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int xen_selfballoon_init(bool use_selfballooning, bool use_frontswap_selfshrink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xen-selfballoon.c (0)
Location: drivers/xen/xen-selfballoon.c:527
Inline: False
```
**Symbols:**

```
ffffffff8161ca74-ffffffff8161cb07: xen_selfballoon_init.cold.1 (STB_LOCAL)
ffffffff8161ca20-ffffffff8161ca74: xen_selfballoon_init (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
