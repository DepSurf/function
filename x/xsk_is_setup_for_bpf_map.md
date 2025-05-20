# Function: <code>xsk_is_setup_for_bpf_map</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
bool xsk_is_setup_for_bpf_map(struct xdp_sock *xs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff819cc5c0)
Location: net/xdp/xsk.c:38
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffffffff819cc5c0-ffffffff819cc5f5: xsk_is_setup_for_bpf_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool xsk_is_setup_for_bpf_map(struct xdp_sock *xs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81a05630)
Location: net/xdp/xsk.c:38
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffffffff81a05630-ffffffff81a05665: xsk_is_setup_for_bpf_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool xsk_is_setup_for_bpf_map(struct xdp_sock *xs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81a74f40)
Location: net/xdp/xsk.c:34
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffffffff81a74f40-ffffffff81a74f75: xsk_is_setup_for_bpf_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool xsk_is_setup_for_bpf_map(struct xdp_sock *xs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81aabbf0)
Location: net/xdp/xsk.c:34
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffffffff81aabbf0-ffffffff81aabc25: xsk_is_setup_for_bpf_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool xsk_is_setup_for_bpf_map(struct xdp_sock *xs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ba8010)
Location: net/xdp/xsk.c:36
Inline: False
Direct callers:
  - net/xdp/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffffffff81ba8010-ffffffff81ba8045: xsk_is_setup_for_bpf_map (STB_GLOBAL)
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
bool xsk_is_setup_for_bpf_map(struct xdp_sock *xs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffff800010d802e8)
Location: net/xdp/xsk.c:34
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffff800010d802e8-ffff800010d80340: xsk_is_setup_for_bpf_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool xsk_is_setup_for_bpf_map(struct xdp_sock *xs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (c0e7a6cc)
Location: net/xdp/xsk.c:34
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
c0e7a6cc-c0e7a714: xsk_is_setup_for_bpf_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool xsk_is_setup_for_bpf_map(struct xdp_sock *xs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (c000000000ebfe70)
Location: net/xdp/xsk.c:34
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
c000000000ebfe70-c000000000ebfeb8: xsk_is_setup_for_bpf_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool xsk_is_setup_for_bpf_map(struct xdp_sock *xs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffe0008acb9a)
Location: net/xdp/xsk.c:34
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffffffe0008acb9a-ffffffe0008acbd4: xsk_is_setup_for_bpf_map (STB_GLOBAL)
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
bool xsk_is_setup_for_bpf_map(struct xdp_sock *xs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81a4af80)
Location: net/xdp/xsk.c:34
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffffffff81a4af80-ffffffff81a4afb5: xsk_is_setup_for_bpf_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool xsk_is_setup_for_bpf_map(struct xdp_sock *xs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81a07b70)
Location: net/xdp/xsk.c:34
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffffffff81a07b70-ffffffff81a07ba5: xsk_is_setup_for_bpf_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool xsk_is_setup_for_bpf_map(struct xdp_sock *xs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ab6e30)
Location: net/xdp/xsk.c:34
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffffffff81ab6e30-ffffffff81ab6e65: xsk_is_setup_for_bpf_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool xsk_is_setup_for_bpf_map(struct xdp_sock *xs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ac3250)
Location: net/xdp/xsk.c:34
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffffffff81ac3250-ffffffff81ac3285: xsk_is_setup_for_bpf_map (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
