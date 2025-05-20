# Function: <code>setup_swap_info</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void setup_swap_info(struct swap_info_struct *p, int prio, unsigned char *swap_map, struct swap_cluster_info *cluster_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81278170)
Location: mm/swapfile.c:2422
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
**Symbols:**

```
ffffffff81278170-ffffffff81278273: setup_swap_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void setup_swap_info(struct swap_info_struct *p, int prio, unsigned char *swap_map, struct swap_cluster_info *cluster_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81287c60)
Location: mm/swapfile.c:2421
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
**Symbols:**

```
ffffffff81287c60-ffffffff81287d63: setup_swap_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void setup_swap_info(struct swap_info_struct *p, int prio, unsigned char *swap_map, struct swap_cluster_info *cluster_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812ba020)
Location: mm/swapfile.c:2451
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:enable_swap_info
```
**Symbols:**

```
ffffffff812ba020-ffffffff812ba123: setup_swap_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void setup_swap_info(struct swap_info_struct *p, int prio, unsigned char *swap_map, struct swap_cluster_info *cluster_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812c5a90)
Location: mm/swapfile.c:2467
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:enable_swap_info
```
**Symbols:**

```
ffffffff812c5a90-ffffffff812c5b93: setup_swap_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void setup_swap_info(struct swap_info_struct *p, int prio, unsigned char *swap_map, struct swap_cluster_info *cluster_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812ccc40)
Location: mm/swapfile.c:2438
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:enable_swap_info
```
**Symbols:**

```
ffffffff812ccc40-ffffffff812ccd43: setup_swap_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void setup_swap_info(struct swap_info_struct *p, int prio, unsigned char *swap_map, struct swap_cluster_info *cluster_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81311f30)
Location: mm/swapfile.c:2425
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:enable_swap_info
```
**Symbols:**

```
ffffffff81311f30-ffffffff81312033: setup_swap_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void setup_swap_info(struct swap_info_struct *p, int prio, unsigned char *swap_map, struct swap_cluster_info *cluster_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8137d430)
Location: mm/swapfile.c:2293
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
**Symbols:**

```
ffffffff8137d430-ffffffff8137d52e: setup_swap_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void setup_swap_info(struct swap_info_struct *p, int prio, unsigned char *swap_map, struct swap_cluster_info *cluster_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff813fa450)
Location: mm/swapfile.c:2295
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
**Symbols:**

```
ffffffff813fa450-ffffffff813fa540: setup_swap_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void setup_swap_info(struct swap_info_struct *p, int prio, unsigned char *swap_map, struct swap_cluster_info *cluster_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8142d390)
Location: mm/swapfile.c:2286
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
**Symbols:**

```
ffffffff8142d390-ffffffff8142d480: setup_swap_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void setup_swap_info(struct swap_info_struct *p, int prio, unsigned char *swap_map, struct swap_cluster_info *cluster_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81466b00)
Location: mm/swapfile.c:2294
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
**Symbols:**

```
ffffffff81466b00-ffffffff81466bf0: setup_swap_info (STB_LOCAL)
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
void setup_swap_info(struct swap_info_struct *p, int prio, unsigned char *swap_map, struct swap_cluster_info *cluster_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffff800010322a50)
Location: mm/swapfile.c:2421
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:enable_swap_info
```
**Symbols:**

```
ffff800010322a50-ffff800010322ba0: setup_swap_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void setup_swap_info(struct swap_info_struct *p, int prio, unsigned char *swap_map, struct swap_cluster_info *cluster_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c053acb0)
Location: mm/swapfile.c:2421
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
**Symbols:**

```
c053acb0-c053ad58: setup_swap_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void setup_swap_info(struct swap_info_struct *p, int prio, unsigned char *swap_map, struct swap_cluster_info *cluster_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c0000000003f8570)
Location: mm/swapfile.c:2421
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
**Symbols:**

```
c0000000003f8570-c0000000003f86fc: setup_swap_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void setup_swap_info(struct swap_info_struct *p, int prio, unsigned char *swap_map, struct swap_cluster_info *cluster_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffe000223542)
Location: mm/swapfile.c:2421
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
**Symbols:**

```
ffffffe000223542-ffffffe0002235da: setup_swap_info (STB_LOCAL)
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
void setup_swap_info(struct swap_info_struct *p, int prio, unsigned char *swap_map, struct swap_cluster_info *cluster_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81280240)
Location: mm/swapfile.c:2421
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
**Symbols:**

```
ffffffff81280240-ffffffff81280343: setup_swap_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void setup_swap_info(struct swap_info_struct *p, int prio, unsigned char *swap_map, struct swap_cluster_info *cluster_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812720b0)
Location: mm/swapfile.c:2421
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
**Symbols:**

```
ffffffff812720b0-ffffffff812721b3: setup_swap_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void setup_swap_info(struct swap_info_struct *p, int prio, unsigned char *swap_map, struct swap_cluster_info *cluster_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8127e050)
Location: mm/swapfile.c:2421
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
**Symbols:**

```
ffffffff8127e050-ffffffff8127e153: setup_swap_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void setup_swap_info(struct swap_info_struct *p, int prio, unsigned char *swap_map, struct swap_cluster_info *cluster_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8128dc00)
Location: mm/swapfile.c:2421
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
**Symbols:**

```
ffffffff8128dc00-ffffffff8128dd03: setup_swap_info (STB_LOCAL)
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
