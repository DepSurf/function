# Function: <code>generic_swapfile_activate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int generic_swapfile_activate(struct swap_info_struct *sis, struct file *swap_file, sector_t *span);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff811d2030)
Location: mm/page_io.c:132
Inline: False
Direct callers:
  - mm/swapfile.c:SyS_swapon
```
**Symbols:**

```
ffffffff811d2030-ffffffff811d224a: generic_swapfile_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int generic_swapfile_activate(struct swap_info_struct *sis, struct file *swap_file, sector_t *span);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff811efb90)
Location: mm/page_io.c:138
Inline: False
Direct callers:
  - mm/swapfile.c:SyS_swapon
```
**Symbols:**

```
ffffffff811efb90-ffffffff811efdb3: generic_swapfile_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int generic_swapfile_activate(struct swap_info_struct *sis, struct file *swap_file, sector_t *span);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff81200530)
Location: mm/page_io.c:138
Inline: False
Direct callers:
  - mm/swapfile.c:SyS_swapon
```
**Symbols:**

```
ffffffff81200530-ffffffff81200753: generic_swapfile_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int generic_swapfile_activate(struct swap_info_struct *sis, struct file *swap_file, sector_t *span);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff8120b190)
Location: mm/page_io.c:143
Inline: False
Direct callers:
  - mm/swapfile.c:SyS_swapon
```
**Symbols:**

```
ffffffff8120b190-ffffffff8120b39a: generic_swapfile_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int generic_swapfile_activate(struct swap_info_struct *sis, struct file *swap_file, sector_t *span);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff81224650)
Location: mm/page_io.c:147
Inline: False
Direct callers:
  - mm/swapfile.c:SYSC_swapon
```
**Symbols:**

```
ffffffff81224650-ffffffff81224860: generic_swapfile_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int generic_swapfile_activate(struct swap_info_struct *sis, struct file *swap_file, sector_t *span);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_io.c (0)
Location: mm/page_io.c:147
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
```
**Symbols:**

```
ffffffff81247463-ffffffff81247479: generic_swapfile_activate.cold.9 (STB_LOCAL)
ffffffff81246c00-ffffffff81246de2: generic_swapfile_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int generic_swapfile_activate(struct swap_info_struct *sis, struct file *swap_file, sector_t *span);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_io.c (0)
Location: mm/page_io.c:147
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
```
**Symbols:**

```
ffffffff8125b8d7-ffffffff8125b8ed: generic_swapfile_activate.cold.9 (STB_LOCAL)
ffffffff8125b030-ffffffff8125b207: generic_swapfile_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int generic_swapfile_activate(struct swap_info_struct *sis, struct file *swap_file, sector_t *span);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_io.c (0)
Location: mm/page_io.c:146
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
```
**Symbols:**

```
ffffffff81276a3a-ffffffff81276a51: generic_swapfile_activate.cold (STB_LOCAL)
ffffffff81276130-ffffffff81276342: generic_swapfile_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int generic_swapfile_activate(struct swap_info_struct *sis, struct file *swap_file, sector_t *span);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_io.c (0)
Location: mm/page_io.c:146
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
```
**Symbols:**

```
ffffffff8128652a-ffffffff81286541: generic_swapfile_activate.cold (STB_LOCAL)
ffffffff81285c20-ffffffff81285e32: generic_swapfile_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int generic_swapfile_activate(struct swap_info_struct *sis, struct file *swap_file, sector_t *span);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_io.c (0)
Location: mm/page_io.c:146
Inline: False
Direct callers:
  - mm/swapfile.c:setup_swap_extents
```
**Symbols:**

```
ffffffff812b885e-ffffffff812b8876: generic_swapfile_activate.cold (STB_LOCAL)
ffffffff812b7f10-ffffffff812b815b: generic_swapfile_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int generic_swapfile_activate(struct swap_info_struct *sis, struct file *swap_file, sector_t *span);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_io.c (0)
Location: mm/page_io.c:146
Inline: False
Direct callers:
  - mm/swapfile.c:setup_swap_extents
```
**Symbols:**

```
ffffffff81be86c8-ffffffff81be86e0: generic_swapfile_activate.cold (STB_LOCAL)
ffffffff812c35c0-ffffffff812c380b: generic_swapfile_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int generic_swapfile_activate(struct swap_info_struct *sis, struct file *swap_file, sector_t *span);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_io.c (0)
Location: mm/page_io.c:127
Inline: False
Direct callers:
  - mm/swapfile.c:setup_swap_map_and_extents
```
**Symbols:**

```
ffffffff81bda622-ffffffff81bda63a: generic_swapfile_activate.cold (STB_LOCAL)
ffffffff812ca300-ffffffff812ca544: generic_swapfile_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int generic_swapfile_activate(struct swap_info_struct *sis, struct file *swap_file, sector_t *span);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_io.c (0)
Location: mm/page_io.c:127
Inline: False
Direct callers:
  - mm/swapfile.c:setup_swap_map_and_extents
```
**Symbols:**

```
ffffffff81cbe8d9-ffffffff81cbe960: generic_swapfile_activate.cold (STB_LOCAL)
ffffffff8130f320-ffffffff8130f54b: generic_swapfile_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int generic_swapfile_activate(struct swap_info_struct *sis, struct file *swap_file, sector_t *span);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_io.c (0)
Location: mm/page_io.c:80
Inline: False
Direct callers:
  - mm/swapfile.c:setup_swap_map_and_extents
```
**Symbols:**

```
ffffffff81e70957-ffffffff81e709ef: generic_swapfile_activate.cold (STB_LOCAL)
ffffffff81379600-ffffffff81379851: generic_swapfile_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int generic_swapfile_activate(struct swap_info_struct *sis, struct file *swap_file, sector_t *span);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_io.c (0)
Location: mm/page_io.c:80
Inline: False
Direct callers:
  - mm/swapfile.c:setup_swap_map_and_extents
```
**Symbols:**

```
ffffffff820658e6-ffffffff8206595e: generic_swapfile_activate.cold (STB_LOCAL)
ffffffff813f7080-ffffffff813f72cf: generic_swapfile_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int generic_swapfile_activate(struct swap_info_struct *sis, struct file *swap_file, sector_t *span);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_io.c (0)
Location: mm/page_io.c:81
Inline: False
Direct callers:
  - mm/swapfile.c:setup_swap_map_and_extents
```
**Symbols:**

```
ffffffff820e5118-ffffffff820e5184: generic_swapfile_activate.cold (STB_LOCAL)
ffffffff8142a350-ffffffff8142a5bf: generic_swapfile_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int generic_swapfile_activate(struct swap_info_struct *sis, struct file *swap_file, sector_t *span);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_io.c (0)
Location: mm/page_io.c:78
Inline: False
Direct callers:
  - mm/swapfile.c:setup_swap_map_and_extents
```
**Symbols:**

```
ffffffff821c22ee-ffffffff821c235a: generic_swapfile_activate.cold (STB_LOCAL)
ffffffff81463a10-ffffffff81463c7f: generic_swapfile_activate (STB_GLOBAL)
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
int generic_swapfile_activate(struct swap_info_struct *sis, struct file *swap_file, sector_t *span);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffff8000103201a8)
Location: mm/page_io.c:146
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
```
**Symbols:**

```
ffff8000103201a8-ffff8000103203e4: generic_swapfile_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int generic_swapfile_activate(struct swap_info_struct *sis, struct file *swap_file, sector_t *span);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (c0538afc)
Location: mm/page_io.c:146
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
```
**Symbols:**

```
c0538afc-c0538e9c: generic_swapfile_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int generic_swapfile_activate(struct swap_info_struct *sis, struct file *swap_file, sector_t *span);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (c0000000003f51c0)
Location: mm/page_io.c:146
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
```
**Symbols:**

```
c0000000003f51c0-c0000000003f5514: generic_swapfile_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int generic_swapfile_activate(struct swap_info_struct *sis, struct file *swap_file, sector_t *span);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffe00022195e)
Location: mm/page_io.c:146
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
```
**Symbols:**

```
ffffffe00022195e-ffffffe000221b50: generic_swapfile_activate (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int generic_swapfile_activate(struct swap_info_struct *sis, struct file *swap_file, sector_t *span);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_io.c (0)
Location: mm/page_io.c:146
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
```
**Symbols:**

```
ffffffff8127eb7a-ffffffff8127eb91: generic_swapfile_activate.cold (STB_LOCAL)
ffffffff8127e270-ffffffff8127e482: generic_swapfile_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int generic_swapfile_activate(struct swap_info_struct *sis, struct file *swap_file, sector_t *span);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_io.c (0)
Location: mm/page_io.c:146
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
```
**Symbols:**

```
ffffffff812709aa-ffffffff812709c1: generic_swapfile_activate.cold (STB_LOCAL)
ffffffff812700a0-ffffffff812702b2: generic_swapfile_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int generic_swapfile_activate(struct swap_info_struct *sis, struct file *swap_file, sector_t *span);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_io.c (0)
Location: mm/page_io.c:146
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
```
**Symbols:**

```
ffffffff8127c91a-ffffffff8127c931: generic_swapfile_activate.cold (STB_LOCAL)
ffffffff8127c010-ffffffff8127c222: generic_swapfile_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int generic_swapfile_activate(struct swap_info_struct *sis, struct file *swap_file, sector_t *span);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_io.c (0)
Location: mm/page_io.c:146
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
```
**Symbols:**

```
ffffffff8128c4ea-ffffffff8128c501: generic_swapfile_activate.cold (STB_LOCAL)
ffffffff8128bbf0-ffffffff8128bdfd: generic_swapfile_activate (STB_GLOBAL)
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
