# Function: <code>balloon_append</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff814c6636)
Location: drivers/xen/balloon.c:181
Inline: True
Inline callers:
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/balloon.c:free_xenballooned_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff81516f1d)
Location: drivers/xen/balloon.c:180
Inline: True
Inline callers:
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:decrease_reservation
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff81543396)
Location: drivers/xen/balloon.c:180
Inline: True
Inline callers:
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:decrease_reservation
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff81557226)
Location: drivers/xen/balloon.c:181
Inline: True
Inline callers:
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:decrease_reservation
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff815bb236)
Location: drivers/xen/balloon.c:181
Inline: True
Inline callers:
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:decrease_reservation
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff815f38d6)
Location: drivers/xen/balloon.c:181
Inline: True
Inline callers:
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:decrease_reservation
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
In drivers/xen/balloon.c (ffffffff8160e8f6)
Location: drivers/xen/balloon.c:175
Inline: True
Inline callers:
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:decrease_reservation
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff8164268e)
Location: drivers/xen/balloon.c:172
Inline: True
Inline callers:
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:decrease_reservation
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void balloon_append(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff816648d0)
Location: drivers/xen/balloon.c:159
Inline: False
Direct callers:
  - drivers/xen/balloon.c:balloon_init
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/balloon.c:xen_online_page
```
**Symbols:**

```
ffffffff816648d0-ffffffff81664924: balloon_append (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff82d16c99)
Location: drivers/xen/balloon.c:158
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/balloon.c:xen_online_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff81731657)
Location: drivers/xen/balloon.c:157
Inline: True
Inline callers:
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/balloon.c:xen_online_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff81715057)
Location: drivers/xen/balloon.c:157
Inline: True
Inline callers:
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/balloon.c:xen_online_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff81792067)
Location: drivers/xen/balloon.c:164
Inline: True
Inline callers:
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/balloon.c:xen_online_page
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
In drivers/xen/balloon.c (ffffffff834b0a53)
Location: drivers/xen/balloon.c:166
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
  - drivers/xen/balloon.c:xen_free_ballooned_pages
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/balloon.c:xen_online_page
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
In drivers/xen/balloon.c (ffffffff83eea60f)
Location: drivers/xen/balloon.c:166
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
  - drivers/xen/balloon.c:xen_free_ballooned_pages
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/balloon.c:xen_online_page
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
In drivers/xen/balloon.c (ffffffff83710000)
Location: drivers/xen/balloon.c:148
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
  - drivers/xen/balloon.c:xen_free_ballooned_pages
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/balloon.c:xen_online_page
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
In drivers/xen/balloon.c (ffffffff83943975)
Location: drivers/xen/balloon.c:147
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_init
  - drivers/xen/balloon.c:xen_free_ballooned_pages
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/balloon.c:xen_online_page
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
void balloon_append(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffff80001082e648)
Location: drivers/xen/balloon.c:159
Inline: False
Direct callers:
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/balloon.c:xen_online_page
```
**Symbols:**

```
ffff80001082e648-ffff80001082e6bc: balloon_append (STB_LOCAL)
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
void balloon_append(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff8162a740)
Location: drivers/xen/balloon.c:159
Inline: False
Direct callers:
  - drivers/xen/balloon.c:balloon_init
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:decrease_reservation
```
**Symbols:**

```
ffffffff8162a740-ffffffff8162a794: balloon_append (STB_LOCAL)
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
void balloon_append(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff81658710)
Location: drivers/xen/balloon.c:159
Inline: False
Direct callers:
  - drivers/xen/balloon.c:balloon_init
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/balloon.c:xen_online_page
```
**Symbols:**

```
ffffffff81658710-ffffffff81658764: balloon_append (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void balloon_append(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff81672d10)
Location: drivers/xen/balloon.c:159
Inline: False
Direct callers:
  - drivers/xen/balloon.c:balloon_init
  - drivers/xen/balloon.c:free_xenballooned_pages
  - drivers/xen/balloon.c:decrease_reservation
  - drivers/xen/balloon.c:xen_online_page
```
**Symbols:**

```
ffffffff81672d10-ffffffff81672d64: balloon_append (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
