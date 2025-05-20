# Function: <code>padata_alloc_possible</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct padata_instance *padata_alloc_possible(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff8118a8e0)
Location: kernel/padata.c:1022
Inline: False
```
**Symbols:**

```
ffffffff8118a8e0-ffffffff8118a8fa: padata_alloc_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct padata_instance *padata_alloc_possible(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff8119d220)
Location: kernel/padata.c:959
Inline: False
```
**Symbols:**

```
ffffffff8119d220-ffffffff8119d23a: padata_alloc_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct padata_instance *padata_alloc_possible(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff811acbf0)
Location: kernel/padata.c:947
Inline: False
```
**Symbols:**

```
ffffffff811acbf0-ffffffff811acc0a: padata_alloc_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct padata_instance *padata_alloc_possible(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff811b3510)
Location: kernel/padata.c:1007
Inline: False
```
**Symbols:**

```
ffffffff811b3510-ffffffff811b36d5: padata_alloc_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct padata_instance *padata_alloc_possible(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff811c7180)
Location: kernel/padata.c:1072
Inline: False
```
**Symbols:**

```
ffffffff811c7180-ffffffff811c7345: padata_alloc_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct padata_instance *padata_alloc_possible(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/padata.c (0)
Location: kernel/padata.c:1073
Inline: False
```
**Symbols:**

```
ffffffff811e82ab-ffffffff811e82b7: padata_alloc_possible.cold.18 (STB_LOCAL)
ffffffff811e7f40-ffffffff811e8103: padata_alloc_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct padata_instance *padata_alloc_possible(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/padata.c (0)
Location: kernel/padata.c:1073
Inline: False
```
**Symbols:**

```
ffffffff811f8ed4-ffffffff811f8ee0: padata_alloc_possible.cold.18 (STB_LOCAL)
ffffffff811f8120-ffffffff811f82e3: padata_alloc_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct padata_instance *padata_alloc_possible(struct workqueue_struct *wq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff81210d70)
Location: kernel/padata.c:1086
Inline: False
```
**Symbols:**

```
ffffffff81210d70-ffffffff81210d8f: padata_alloc_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct padata_instance *padata_alloc_possible(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff8121e5d0)
Location: kernel/padata.c:1059
Inline: False
```
**Symbols:**

```
ffffffff8121e5d0-ffffffff8121e5e0: padata_alloc_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct padata_instance *padata_alloc_possible(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff8124a560)
Location: kernel/padata.c:1147
Inline: False
```
**Symbols:**

```
ffffffff8124a560-ffffffff8124a570: padata_alloc_possible (STB_GLOBAL)
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
struct padata_instance *padata_alloc_possible(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffff8000102aa488)
Location: kernel/padata.c:1059
Inline: False
```
**Symbols:**

```
ffff8000102aa488-ffff8000102aa4b4: padata_alloc_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct padata_instance *padata_alloc_possible(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (c04d8d08)
Location: kernel/padata.c:1059
Inline: False
```
**Symbols:**

```
c04d8d08-c04d8d24: padata_alloc_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct padata_instance *padata_alloc_possible(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (c00000000035e470)
Location: kernel/padata.c:1059
Inline: False
```
**Symbols:**

```
c00000000035e470-c00000000035e484: padata_alloc_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct padata_instance *padata_alloc_possible(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffe0001d2c00)
Location: kernel/padata.c:1059
Inline: False
```
**Symbols:**

```
ffffffe0001d2c00-ffffffe0001d2d44: padata_alloc_possible (STB_GLOBAL)
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
struct padata_instance *padata_alloc_possible(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff81216c20)
Location: kernel/padata.c:1059
Inline: False
```
**Symbols:**

```
ffffffff81216c20-ffffffff81216c30: padata_alloc_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct padata_instance *padata_alloc_possible(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff81209980)
Location: kernel/padata.c:1059
Inline: False
```
**Symbols:**

```
ffffffff81209980-ffffffff81209990: padata_alloc_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct padata_instance *padata_alloc_possible(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff812149c0)
Location: kernel/padata.c:1059
Inline: False
```
**Symbols:**

```
ffffffff812149c0-ffffffff812149d0: padata_alloc_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct padata_instance *padata_alloc_possible(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff81223970)
Location: kernel/padata.c:1059
Inline: False
```
**Symbols:**

```
ffffffff81223970-ffffffff81223980: padata_alloc_possible (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char *name</code>
</li>
<li>
<b>Param removed. </b>
<code>struct workqueue_struct *wq</code>
</li>
</ul>
</details>
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
