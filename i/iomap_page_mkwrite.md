# Function: <code>iomap_page_mkwrite</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int iomap_page_mkwrite(struct vm_area_struct *vma, struct vm_fault *vmf, struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff8129c150)
Location: fs/iomap.c:366
Inline: False
```
**Symbols:**

```
ffffffff8129c150-ffffffff8129c250: iomap_page_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int iomap_page_mkwrite(struct vm_area_struct *vma, struct vm_fault *vmf, struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff812b1c80)
Location: fs/iomap.c:448
Inline: False
```
**Symbols:**

```
ffffffff812b1c80-ffffffff812b1d80: iomap_page_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int iomap_page_mkwrite(struct vm_fault *vmf, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff812befb0)
Location: fs/iomap.c:444
Inline: False
```
**Symbols:**

```
ffffffff812befb0-ffffffff812bf0aa: iomap_page_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int iomap_page_mkwrite(struct vm_fault *vmf, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff812e2a20)
Location: fs/iomap.c:444
Inline: False
```
**Symbols:**

```
ffffffff812e2a20-ffffffff812e2b6c: iomap_page_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int iomap_page_mkwrite(struct vm_fault *vmf, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff8130f3c0)
Location: fs/iomap.c:451
Inline: False
```
**Symbols:**

```
ffffffff8130f3c0-ffffffff8130f50b: iomap_page_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
vm_fault_t iomap_page_mkwrite(struct vm_fault *vmf, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff81326330)
Location: fs/iomap.c:1086
Inline: False
```
**Symbols:**

```
ffffffff81326330-ffffffff81326473: iomap_page_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
vm_fault_t iomap_page_mkwrite(struct vm_fault *vmf, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8134b380)
Location: fs/iomap/buffered-io.c:1033
Inline: False
```
**Symbols:**

```
ffffffff8134b380-ffffffff8134b4c3: iomap_page_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
vm_fault_t iomap_page_mkwrite(struct vm_fault *vmf, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81363630)
Location: fs/iomap/buffered-io.c:1033
Inline: False
```
**Symbols:**

```
ffffffff81363630-ffffffff81363773: iomap_page_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
vm_fault_t iomap_page_mkwrite(struct vm_fault *vmf, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813aa440)
Location: fs/iomap/buffered-io.c:1038
Inline: False
```
**Symbols:**

```
ffffffff813aa440-ffffffff813aa58c: iomap_page_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
vm_fault_t iomap_page_mkwrite(struct vm_fault *vmf, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813bba90)
Location: fs/iomap/buffered-io.c:1007
Inline: False
```
**Symbols:**

```
ffffffff813bba90-ffffffff813bbbdc: iomap_page_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
vm_fault_t iomap_page_mkwrite(struct vm_fault *vmf, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813c2b80)
Location: fs/iomap/buffered-io.c:1007
Inline: False
```
**Symbols:**

```
ffffffff813c2b80-ffffffff813c2ccc: iomap_page_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
vm_fault_t iomap_page_mkwrite(struct vm_fault *vmf, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81412d20)
Location: fs/iomap/buffered-io.c:981
Inline: False
```
**Symbols:**

```
ffffffff81412d20-ffffffff81412f46: iomap_page_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
vm_fault_t iomap_page_mkwrite(struct vm_fault *vmf, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:979
Inline: False
```
**Symbols:**

```
ffffffff81e7a23d-ffffffff81e7a289: iomap_page_mkwrite.cold (STB_LOCAL)
ffffffff8148a800-ffffffff8148ab91: iomap_page_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
vm_fault_t iomap_page_mkwrite(struct vm_fault *vmf, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:1240
Inline: False
```
**Symbols:**

```
ffffffff8206b1a8-ffffffff8206b1f4: iomap_page_mkwrite.cold (STB_LOCAL)
ffffffff8151e0b0-ffffffff8151e38a: iomap_page_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
vm_fault_t iomap_page_mkwrite(struct vm_fault *vmf, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:1260
Inline: False
```
**Symbols:**

```
ffffffff820eb0f6-ffffffff820eb142: iomap_page_mkwrite.cold (STB_LOCAL)
ffffffff81556210-ffffffff815564f0: iomap_page_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
vm_fault_t iomap_page_mkwrite(struct vm_fault *vmf, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:1428
Inline: False
```
**Symbols:**

```
ffffffff821c81f5-ffffffff821c823d: iomap_page_mkwrite.cold (STB_LOCAL)
ffffffff8158c6e0-ffffffff8158c9b8: iomap_page_mkwrite (STB_GLOBAL)
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
vm_fault_t iomap_page_mkwrite(struct vm_fault *vmf, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffff80001042a370)
Location: fs/iomap/buffered-io.c:1033
Inline: False
```
**Symbols:**

```
ffff80001042a370-ffff80001042a528: iomap_page_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
vm_fault_t iomap_page_mkwrite(struct vm_fault *vmf, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (c05f3184)
Location: fs/iomap/buffered-io.c:1033
Inline: False
```
**Symbols:**

```
c05f3184-c05f3394: iomap_page_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
vm_fault_t iomap_page_mkwrite(struct vm_fault *vmf, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (c00000000053ac90)
Location: fs/iomap/buffered-io.c:1033
Inline: False
```
**Symbols:**

```
c00000000053ac90-c00000000053aee8: iomap_page_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
vm_fault_t iomap_page_mkwrite(struct vm_fault *vmf, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffe0002c7eca)
Location: fs/iomap/buffered-io.c:1033
Inline: False
```
**Symbols:**

```
ffffffe0002c7eca-ffffffe0002c7ff2: iomap_page_mkwrite (STB_GLOBAL)
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
vm_fault_t iomap_page_mkwrite(struct vm_fault *vmf, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8135bc10)
Location: fs/iomap/buffered-io.c:1033
Inline: False
```
**Symbols:**

```
ffffffff8135bc10-ffffffff8135bd53: iomap_page_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
vm_fault_t iomap_page_mkwrite(struct vm_fault *vmf, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8134c8b0)
Location: fs/iomap/buffered-io.c:1033
Inline: False
```
**Symbols:**

```
ffffffff8134c8b0-ffffffff8134c9f3: iomap_page_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
vm_fault_t iomap_page_mkwrite(struct vm_fault *vmf, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813596e0)
Location: fs/iomap/buffered-io.c:1033
Inline: False
```
**Symbols:**

```
ffffffff813596e0-ffffffff81359823: iomap_page_mkwrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
vm_fault_t iomap_page_mkwrite(struct vm_fault *vmf, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8136cde0)
Location: fs/iomap/buffered-io.c:1033
Inline: False
```
**Symbols:**

```
ffffffff8136cde0-ffffffff8136cf1e: iomap_page_mkwrite (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct vm_area_struct *vma</code>
</li>
<li>
<b>Param reordered. </b>
<code>vma, vmf, ops</code> ➡️ <code>vmf, ops</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct iomap_ops *ops</code> ➡️ <code>const struct iomap_ops *ops</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>vm_fault_t</code>
</li>
</ul>
</details>
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
