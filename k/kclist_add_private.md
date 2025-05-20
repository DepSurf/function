# Function: <code>kclist_add_private</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kclist_add_private(long unsigned int pfn, long unsigned int nr_pages, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff81286ec0)
Location: fs/proc/kcore.c:206
Inline: False
```
**Symbols:**

```
ffffffff81286ec0-ffffffff812870b0: kclist_add_private (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kclist_add_private(long unsigned int pfn, long unsigned int nr_pages, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff812b40a0)
Location: fs/proc/kcore.c:206
Inline: False
```
**Symbols:**

```
ffffffff812b40a0-ffffffff812b42b1: kclist_add_private (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kclist_add_private(long unsigned int pfn, long unsigned int nr_pages, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff812c9940)
Location: fs/proc/kcore.c:206
Inline: False
```
**Symbols:**

```
ffffffff812c9940-ffffffff812c9b4e: kclist_add_private (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kclist_add_private(long unsigned int pfn, long unsigned int nr_pages, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff812d6e10)
Location: fs/proc/kcore.c:207
Inline: False
```
**Symbols:**

```
ffffffff812d6e10-ffffffff812d7000: kclist_add_private (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kclist_add_private(long unsigned int pfn, long unsigned int nr_pages, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff812fb590)
Location: fs/proc/kcore.c:208
Inline: False
```
**Symbols:**

```
ffffffff812fb590-ffffffff812fb780: kclist_add_private (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int kclist_add_private(long unsigned int pfn, long unsigned int nr_pages, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff81328b60)
Location: fs/proc/kcore.c:208
Inline: True
```
**Symbols:**

```
ffffffff81328b60-ffffffff81328dbe: kclist_add_private (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int kclist_add_private(long unsigned int pfn, long unsigned int nr_pages, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff8133f9a0)
Location: fs/proc/kcore.c:163
Inline: True
```
**Symbols:**

```
ffffffff8133f9a0-ffffffff8133fbfe: kclist_add_private (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int kclist_add_private(long unsigned int pfn, long unsigned int nr_pages, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff81367c90)
Location: fs/proc/kcore.c:185
Inline: True
```
**Symbols:**

```
ffffffff81367c90-ffffffff81367f03: kclist_add_private (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int kclist_add_private(long unsigned int pfn, long unsigned int nr_pages, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff8137ff10)
Location: fs/proc/kcore.c:186
Inline: True
```
**Symbols:**

```
ffffffff8137ff10-ffffffff81380183: kclist_add_private (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kclist_add_private(long unsigned int pfn, long unsigned int nr_pages, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/kcore.c (ffffffff813ca580)
Location: fs/proc/kcore.c:186
Inline: True
```
**Symbols:**

```
ffffffff813ca6b0-ffffffff813ca73e: kclist_add_private (STB_LOCAL)
ffffffff813ca580-ffffffff813ca6a2: kclist_add_private.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kclist_add_private(long unsigned int pfn, long unsigned int nr_pages, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/kcore.c (ffffffff813dc240)
Location: fs/proc/kcore.c:186
Inline: True
```
**Symbols:**

```
ffffffff813dc370-ffffffff813dc3fe: kclist_add_private (STB_LOCAL)
ffffffff813dc240-ffffffff813dc362: kclist_add_private.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int kclist_add_private(long unsigned int pfn, long unsigned int nr_pages, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff813e30d0)
Location: fs/proc/kcore.c:186
Inline: True
```
**Symbols:**

```
ffffffff813e30d0-ffffffff813e32f4: kclist_add_private (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int kclist_add_private(long unsigned int pfn, long unsigned int nr_pages, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff81434be0)
Location: fs/proc/kcore.c:186
Inline: True
```
**Symbols:**

```
ffffffff81434be0-ffffffff81434e04: kclist_add_private (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kclist_add_private(long unsigned int pfn, long unsigned int nr_pages, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff814aed40)
Location: fs/proc/kcore.c:186
Inline: False
```
**Symbols:**

```
ffffffff814aed40-ffffffff814aefe0: kclist_add_private (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kclist_add_private(long unsigned int pfn, long unsigned int nr_pages, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff815453f0)
Location: fs/proc/kcore.c:185
Inline: False
```
**Symbols:**

```
ffffffff815453f0-ffffffff8154568d: kclist_add_private (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kclist_add_private(long unsigned int pfn, long unsigned int nr_pages, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff8157cfd0)
Location: fs/proc/kcore.c:185
Inline: False
```
**Symbols:**

```
ffffffff8157cfd0-ffffffff8157d26d: kclist_add_private (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kclist_add_private(long unsigned int pfn, long unsigned int nr_pages, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff815b5920)
Location: fs/proc/kcore.c:185
Inline: False
```
**Symbols:**

```
ffffffff815b5920-ffffffff815b5c76: kclist_add_private (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int kclist_add_private(long unsigned int pfn, long unsigned int nr_pages, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffff80001044d678)
Location: fs/proc/kcore.c:186
Inline: True
```
**Symbols:**

```
ffff80001044d678-ffff80001044d8fc: kclist_add_private (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int kclist_add_private(long unsigned int pfn, long unsigned int nr_pages, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (c0000000005654d0)
Location: fs/proc/kcore.c:186
Inline: True
```
**Symbols:**

```
c0000000005654d0-c000000000565854: kclist_add_private (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int kclist_add_private(long unsigned int pfn, long unsigned int nr_pages, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffe0002e24d8)
Location: fs/proc/kcore.c:186
Inline: True
```
**Symbols:**

```
ffffffe0002e24d8-ffffffe0002e26fa: kclist_add_private (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int kclist_add_private(long unsigned int pfn, long unsigned int nr_pages, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff813784f0)
Location: fs/proc/kcore.c:186
Inline: True
```
**Symbols:**

```
ffffffff813784f0-ffffffff81378763: kclist_add_private (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int kclist_add_private(long unsigned int pfn, long unsigned int nr_pages, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff81368fc0)
Location: fs/proc/kcore.c:186
Inline: True
```
**Symbols:**

```
ffffffff81368fc0-ffffffff81369233: kclist_add_private (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int kclist_add_private(long unsigned int pfn, long unsigned int nr_pages, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff81375fc0)
Location: fs/proc/kcore.c:186
Inline: True
```
**Symbols:**

```
ffffffff81375fc0-ffffffff81376233: kclist_add_private (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int kclist_add_private(long unsigned int pfn, long unsigned int nr_pages, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff81389a70)
Location: fs/proc/kcore.c:186
Inline: True
```
**Symbols:**

```
ffffffff81389a70-ffffffff81389ce3: kclist_add_private (STB_LOCAL)
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
