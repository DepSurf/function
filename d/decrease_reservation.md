# Function: <code>decrease_reservation</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
enum bp_state decrease_reservation(long unsigned int nr_pages, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff814c6460)
Location: drivers/xen/balloon.c:467
Inline: False
Direct callers:
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:alloc_xenballooned_pages
```
**Symbols:**

```
ffffffff814c6460-ffffffff814c676d: decrease_reservation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
enum bp_state decrease_reservation(long unsigned int nr_pages, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff81516b90)
Location: drivers/xen/balloon.c:489
Inline: False
Direct callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffffffff81516b90-ffffffff81516eb2: decrease_reservation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
enum bp_state decrease_reservation(long unsigned int nr_pages, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff81543000)
Location: drivers/xen/balloon.c:486
Inline: False
Direct callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffffffff81543000-ffffffff81543328: decrease_reservation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
enum bp_state decrease_reservation(long unsigned int nr_pages, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff81556eb0)
Location: drivers/xen/balloon.c:487
Inline: False
Direct callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffffffff81556eb0-ffffffff815571b8: decrease_reservation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
enum bp_state decrease_reservation(long unsigned int nr_pages, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff815baec0)
Location: drivers/xen/balloon.c:532
Inline: False
Direct callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffffffff815baec0-ffffffff815bb1c4: decrease_reservation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
enum bp_state decrease_reservation(long unsigned int nr_pages, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff815f3570)
Location: drivers/xen/balloon.c:532
Inline: False
Direct callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffffffff815f3570-ffffffff815f3869: decrease_reservation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
enum bp_state decrease_reservation(long unsigned int nr_pages, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff8160e5e0)
Location: drivers/xen/balloon.c:452
Inline: False
Direct callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffffffff8160e5e0-ffffffff8160e88f: decrease_reservation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
enum bp_state decrease_reservation(long unsigned int nr_pages, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff81642360)
Location: drivers/xen/balloon.c:456
Inline: False
Direct callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffffffff81642360-ffffffff81642618: decrease_reservation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
enum bp_state decrease_reservation(long unsigned int nr_pages, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff81664930)
Location: drivers/xen/balloon.c:453
Inline: False
Direct callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffffffff81664930-ffffffff81664be1: decrease_reservation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
enum bp_state decrease_reservation(long unsigned int nr_pages, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff817144b0)
Location: drivers/xen/balloon.c:451
Inline: False
Direct callers:
  - drivers/xen/balloon.c:add_ballooned_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffffffff817144b0-ffffffff817147b4: decrease_reservation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
enum bp_state decrease_reservation(long unsigned int nr_pages, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff81730b90)
Location: drivers/xen/balloon.c:436
Inline: False
Direct callers:
  - drivers/xen/balloon.c:add_ballooned_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffffffff81730b90-ffffffff81730e94: decrease_reservation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
enum bp_state decrease_reservation(long unsigned int nr_pages, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff81714720)
Location: drivers/xen/balloon.c:436
Inline: False
Direct callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffffffff81714720-ffffffff81714a20: decrease_reservation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
enum bp_state decrease_reservation(long unsigned int nr_pages, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/balloon.c (0)
Location: drivers/xen/balloon.c:441
Inline: False
Direct callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_thread
```
**Symbols:**

```
ffffffff81791550-ffffffff81791894: decrease_reservation (STB_LOCAL)
ffffffff81cf5504-ffffffff81cf5527: decrease_reservation.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
enum bp_state decrease_reservation(long unsigned int nr_pages, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/balloon.c (0)
Location: drivers/xen/balloon.c:443
Inline: False
Direct callers:
  - drivers/xen/balloon.c:xen_alloc_ballooned_pages
  - drivers/xen/balloon.c:balloon_thread
```
**Symbols:**

```
ffffffff818ca050-ffffffff818ca37b: decrease_reservation (STB_LOCAL)
ffffffff81ebd694-ffffffff81ebd6af: decrease_reservation.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
enum bp_state decrease_reservation(long unsigned int nr_pages, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/balloon.c (0)
Location: drivers/xen/balloon.c:443
Inline: False
Direct callers:
  - drivers/xen/balloon.c:xen_alloc_ballooned_pages
  - drivers/xen/balloon.c:balloon_thread
```
**Symbols:**

```
ffffffff81a1ac10-ffffffff81a1af3b: decrease_reservation (STB_LOCAL)
ffffffff8209466d-ffffffff82094688: decrease_reservation.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
enum bp_state decrease_reservation(long unsigned int nr_pages, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/balloon.c (0)
Location: drivers/xen/balloon.c:425
Inline: False
Direct callers:
  - drivers/xen/balloon.c:xen_alloc_ballooned_pages
  - drivers/xen/balloon.c:balloon_thread
```
**Symbols:**

```
ffffffff81a63dc0-ffffffff81a640eb: decrease_reservation (STB_LOCAL)
ffffffff821153e2-ffffffff821153fd: decrease_reservation.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
enum bp_state decrease_reservation(long unsigned int nr_pages, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/balloon.c (0)
Location: drivers/xen/balloon.c:424
Inline: False
Direct callers:
  - drivers/xen/balloon.c:xen_alloc_ballooned_pages
  - drivers/xen/balloon.c:balloon_thread
```
**Symbols:**

```
ffffffff81ab6600-ffffffff81ab692b: decrease_reservation (STB_LOCAL)
ffffffff821f3082-ffffffff821f309d: decrease_reservation.cold (STB_LOCAL)
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
enum bp_state decrease_reservation(long unsigned int nr_pages, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffff80001082e6c0)
Location: drivers/xen/balloon.c:453
Inline: False
Direct callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffff80001082e6c0-ffff80001082e8e8: decrease_reservation (STB_LOCAL)
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
enum bp_state decrease_reservation(long unsigned int nr_pages, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff8162a7a0)
Location: drivers/xen/balloon.c:453
Inline: False
Direct callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffffffff8162a7a0-ffffffff8162aa51: decrease_reservation (STB_LOCAL)
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
enum bp_state decrease_reservation(long unsigned int nr_pages, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff81658770)
Location: drivers/xen/balloon.c:453
Inline: False
Direct callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffffffff81658770-ffffffff81658a21: decrease_reservation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
enum bp_state decrease_reservation(long unsigned int nr_pages, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff81672d70)
Location: drivers/xen/balloon.c:453
Inline: False
Direct callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffffffff81672d70-ffffffff8167303f: decrease_reservation (STB_LOCAL)
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
