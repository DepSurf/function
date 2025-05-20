# Function: <code>arch_gnttab_map_status</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int arch_gnttab_map_status(uint64_t *frames, long unsigned int nr_gframes, long unsigned int max_nr_gframes, grant_status_t **__shared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff8101c020)
Location: arch/x86/xen/grant-table.c:76
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_map_frames_v2
```
**Symbols:**

```
ffffffff8101c020-ffffffff8101c0bd: arch_gnttab_map_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int arch_gnttab_map_status(uint64_t *frames, long unsigned int nr_gframes, long unsigned int max_nr_gframes, grant_status_t **__shared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff8101ca10)
Location: arch/x86/xen/grant-table.c:76
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_map_frames_v2
```
**Symbols:**

```
ffffffff8101ca10-ffffffff8101cac4: arch_gnttab_map_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int arch_gnttab_map_status(uint64_t *frames, long unsigned int nr_gframes, long unsigned int max_nr_gframes, grant_status_t **__shared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff8101c2a0)
Location: arch/x86/xen/grant-table.c:53
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_map_frames_v2
```
**Symbols:**

```
ffffffff8101c2a0-ffffffff8101c354: arch_gnttab_map_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int arch_gnttab_map_status(uint64_t *frames, long unsigned int nr_gframes, long unsigned int max_nr_gframes, grant_status_t **__shared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff8101de00)
Location: arch/x86/xen/grant-table.c:53
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_map_frames_v2
```
**Symbols:**

```
ffffffff8101de00-ffffffff8101deb8: arch_gnttab_map_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int arch_gnttab_map_status(uint64_t *frames, long unsigned int nr_gframes, long unsigned int max_nr_gframes, grant_status_t **__shared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff8101e780)
Location: arch/x86/xen/grant-table.c:53
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_map_frames_v2
```
**Symbols:**

```
ffffffff8101e780-ffffffff8101e838: arch_gnttab_map_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int arch_gnttab_map_status(uint64_t *frames, long unsigned int nr_gframes, long unsigned int max_nr_gframes, grant_status_t **__shared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff81020d10)
Location: arch/x86/xen/grant-table.c:52
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_map_frames_v2
```
**Symbols:**

```
ffffffff81020d10-ffffffff81020dbd: arch_gnttab_map_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int arch_gnttab_map_status(uint64_t *frames, long unsigned int nr_gframes, long unsigned int max_nr_gframes, grant_status_t **__shared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff810215a0)
Location: arch/x86/xen/grant-table.c:53
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_map_frames_v2
```
**Symbols:**

```
ffffffff810215a0-ffffffff81021633: arch_gnttab_map_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int arch_gnttab_map_status(uint64_t *frames, long unsigned int nr_gframes, long unsigned int max_nr_gframes, grant_status_t **__shared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff81023930)
Location: arch/x86/xen/grant-table.c:53
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_map_frames_v2
```
**Symbols:**

```
ffffffff81023930-ffffffff810239c0: arch_gnttab_map_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int arch_gnttab_map_status(uint64_t *frames, long unsigned int nr_gframes, long unsigned int max_nr_gframes, grant_status_t **__shared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff81027bd0)
Location: arch/x86/xen/grant-table.c:53
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_map_frames_v2
```
**Symbols:**

```
ffffffff81027bd0-ffffffff81027c60: arch_gnttab_map_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int arch_gnttab_map_status(uint64_t *frames, long unsigned int nr_gframes, long unsigned int max_nr_gframes, grant_status_t **__shared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff8102c030)
Location: arch/x86/xen/grant-table.c:53
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_map_frames_v2
```
**Symbols:**

```
ffffffff8102c030-ffffffff8102c0dd: arch_gnttab_map_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int arch_gnttab_map_status(uint64_t *frames, long unsigned int nr_gframes, long unsigned int max_nr_gframes, grant_status_t **__shared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff81032f60)
Location: arch/x86/xen/grant-table.c:53
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_map_frames_v2
```
**Symbols:**

```
ffffffff81032f60-ffffffff8103300d: arch_gnttab_map_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int arch_gnttab_map_status(uint64_t *frames, long unsigned int nr_gframes, long unsigned int max_nr_gframes, grant_status_t **__shared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff81032f00)
Location: arch/x86/xen/grant-table.c:53
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_map_frames_v2
```
**Symbols:**

```
ffffffff81032f00-ffffffff81032fad: arch_gnttab_map_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int arch_gnttab_map_status(uint64_t *frames, long unsigned int nr_gframes, long unsigned int max_nr_gframes, grant_status_t **__shared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff81039240)
Location: arch/x86/xen/grant-table.c:53
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_map_frames_v2
```
**Symbols:**

```
ffffffff81039240-ffffffff810392e0: arch_gnttab_map_status (STB_GLOBAL)
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
int arch_gnttab_map_status(uint64_t *frames, long unsigned int nr_gframes, long unsigned int max_nr_gframes, grant_status_t **__shared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/xen/grant-table.c (0)
Location: arch/arm/xen/grant-table.c:48
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_map_frames_v2
```
**Symbols:**

```
ffff8000100f0358-ffff8000100f0374: arch_gnttab_map_status (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int arch_gnttab_map_status(uint64_t *frames, long unsigned int nr_gframes, long unsigned int max_nr_gframes, grant_status_t **__shared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff8101e790)
Location: arch/x86/xen/grant-table.c:53
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_map_frames_v2
```
**Symbols:**

```
ffffffff8101e790-ffffffff8101e848: arch_gnttab_map_status (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int arch_gnttab_map_status(uint64_t *frames, long unsigned int nr_gframes, long unsigned int max_nr_gframes, grant_status_t **__shared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff8101e740)
Location: arch/x86/xen/grant-table.c:53
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_map_frames_v2
```
**Symbols:**

```
ffffffff8101e740-ffffffff8101e7f8: arch_gnttab_map_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int arch_gnttab_map_status(uint64_t *frames, long unsigned int nr_gframes, long unsigned int max_nr_gframes, grant_status_t **__shared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/grant-table.c (ffffffff8101e990)
Location: arch/x86/xen/grant-table.c:53
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_map_frames_v2
```
**Symbols:**

```
ffffffff8101e990-ffffffff8101ea48: arch_gnttab_map_status (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
