# Function: <code>mem_xa_remove</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mem_xa_remove(struct xdp_mem_allocator *xa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81962890)
Location: net/core/xdp.c:84
Inline: False
Direct callers:
  - net/core/xdp.c:mem_allocator_disconnect
```
**Symbols:**

```
ffffffff81962890-ffffffff81962a96: mem_xa_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mem_xa_remove(struct xdp_mem_allocator *xa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81a361b0)
Location: net/core/xdp.c:81
Inline: False
Direct callers:
  - net/core/xdp.c:mem_allocator_disconnect
```
**Symbols:**

```
ffffffff81a361b0-ffffffff81a362b7: mem_xa_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mem_xa_remove(struct xdp_mem_allocator *xa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81a38580)
Location: net/core/xdp.c:81
Inline: False
Direct callers:
  - net/core/xdp.c:mem_allocator_disconnect
```
**Symbols:**

```
ffffffff81a38580-ffffffff81a38687: mem_xa_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mem_xa_remove(struct xdp_mem_allocator *xa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81a1f3b0)
Location: net/core/xdp.c:81
Inline: False
Direct callers:
  - net/core/xdp.c:mem_allocator_disconnect
```
**Symbols:**

```
ffffffff81a1f3b0-ffffffff81a1f4b7: mem_xa_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mem_xa_remove(struct xdp_mem_allocator *xa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81ad3650)
Location: net/core/xdp.c:81
Inline: False
Direct callers:
  - net/core/xdp.c:mem_allocator_disconnect
```
**Symbols:**

```
ffffffff81ad3650-ffffffff81ad3757: mem_xa_remove (STB_LOCAL)
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
In net/core/xdp.c (ffffffff81c50faa)
Location: net/core/xdp.c:81
Inline: True
Inline callers:
  - net/core/xdp.c:mem_allocator_disconnect
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
In net/core/xdp.c (ffffffff81e0664a)
Location: net/core/xdp.c:81
Inline: True
Inline callers:
  - net/core/xdp.c:mem_allocator_disconnect
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
In net/core/xdp.c (ffffffff81e78eca)
Location: net/core/xdp.c:83
Inline: True
Inline callers:
  - net/core/xdp.c:mem_allocator_disconnect
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
In net/core/xdp.c (ffffffff81f38d9a)
Location: net/core/xdp.c:83
Inline: True
Inline callers:
  - net/core/xdp.c:mem_allocator_disconnect
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
void mem_xa_remove(struct xdp_mem_allocator *xa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffff800010c05e30)
Location: net/core/xdp.c:84
Inline: False
Direct callers:
  - net/core/xdp.c:mem_allocator_disconnect
```
**Symbols:**

```
ffff800010c05e30-ffff800010c060fc: mem_xa_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mem_xa_remove(struct xdp_mem_allocator *xa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (c0d1f12c)
Location: net/core/xdp.c:84
Inline: False
Direct callers:
  - net/core/xdp.c:mem_allocator_disconnect
```
**Symbols:**

```
c0d1f12c-c0d1f4d0: mem_xa_remove (STB_LOCAL)
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
In net/core/xdp.c (c000000000cf0670)
Location: net/core/xdp.c:84
Inline: True
Inline callers:
  - net/core/xdp.c:mem_allocator_disconnect
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
In net/core/xdp.c (ffffffe00078485a)
Location: net/core/xdp.c:84
Inline: True
Inline callers:
  - net/core/xdp.c:mem_allocator_disconnect
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
void mem_xa_remove(struct xdp_mem_allocator *xa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81902860)
Location: net/core/xdp.c:84
Inline: False
Direct callers:
  - net/core/xdp.c:mem_allocator_disconnect
```
**Symbols:**

```
ffffffff81902860-ffffffff81902a66: mem_xa_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void mem_xa_remove(struct xdp_mem_allocator *xa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff818bc690)
Location: net/core/xdp.c:84
Inline: False
Direct callers:
  - net/core/xdp.c:mem_allocator_disconnect
```
**Symbols:**

```
ffffffff818bc690-ffffffff818bc896: mem_xa_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mem_xa_remove(struct xdp_mem_allocator *xa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81953890)
Location: net/core/xdp.c:84
Inline: False
Direct callers:
  - net/core/xdp.c:mem_allocator_disconnect
```
**Symbols:**

```
ffffffff81953890-ffffffff81953a96: mem_xa_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mem_xa_remove(struct xdp_mem_allocator *xa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff819753b0)
Location: net/core/xdp.c:84
Inline: False
Direct callers:
  - net/core/xdp.c:mem_allocator_disconnect
```
**Symbols:**

```
ffffffff819753b0-ffffffff8197563d: mem_xa_remove (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
