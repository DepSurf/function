# Function: <code>xdp_umem_clear_dev</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff819ccb7c)
Location: net/xdp/xdp_umem.c:96
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
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
In net/xdp/xdp_umem.c (ffffffff81a05c1c)
Location: net/xdp/xdp_umem.c:137
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xdp_umem_clear_dev(struct xdp_umem *umem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81a75880)
Location: net/xdp/xdp_umem.c:139
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_notifier
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff81a75880-ffffffff81a759ca: xdp_umem_clear_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xdp_umem_clear_dev(struct xdp_umem *umem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81aac710)
Location: net/xdp/xdp_umem.c:154
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_notifier
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff81aac710-ffffffff81aac860: xdp_umem_clear_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xdp_umem_clear_dev(struct xdp_umem *umem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81ba89c0)
Location: net/xdp/xdp_umem.c:154
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_notifier
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff81ba89c0-ffffffff81ba8af9: xdp_umem_clear_dev (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void xdp_umem_clear_dev(struct xdp_umem *umem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffff800010d80fd0)
Location: net/xdp/xdp_umem.c:154
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_notifier
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffff800010d80fd0-ffff800010d81118: xdp_umem_clear_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void xdp_umem_clear_dev(struct xdp_umem *umem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (c0e7b4e0)
Location: net/xdp/xdp_umem.c:154
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_notifier
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
c0e7b4e0-c0e7b658: xdp_umem_clear_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void xdp_umem_clear_dev(struct xdp_umem *umem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (c000000000ec0db0)
Location: net/xdp/xdp_umem.c:154
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_notifier
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
c000000000ec0db0-c000000000ec0f68: xdp_umem_clear_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void xdp_umem_clear_dev(struct xdp_umem *umem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffe0008ad4d0)
Location: net/xdp/xdp_umem.c:154
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_notifier
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffe0008ad4d0-ffffffe0008ad5de: xdp_umem_clear_dev (STB_GLOBAL)
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
void xdp_umem_clear_dev(struct xdp_umem *umem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81a4baa0)
Location: net/xdp/xdp_umem.c:154
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_notifier
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff81a4baa0-ffffffff81a4bbf0: xdp_umem_clear_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void xdp_umem_clear_dev(struct xdp_umem *umem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81a08690)
Location: net/xdp/xdp_umem.c:154
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_notifier
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff81a08690-ffffffff81a087e0: xdp_umem_clear_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void xdp_umem_clear_dev(struct xdp_umem *umem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81ab7950)
Location: net/xdp/xdp_umem.c:154
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_notifier
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff81ab7950-ffffffff81ab7aa0: xdp_umem_clear_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xdp_umem_clear_dev(struct xdp_umem *umem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81ac3d70)
Location: net/xdp/xdp_umem.c:154
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_notifier
  - net/xdp/xdp_umem.c:xdp_umem_release_deferred
```
**Symbols:**

```
ffffffff81ac3d70-ffffffff81ac3ec0: xdp_umem_clear_dev (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
