# Function: <code>safe_copy_page</code>

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
In kernel/power/snapshot.c (ffffffff810d1ca5)
Location: kernel/power/snapshot.c:1211
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
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
In kernel/power/snapshot.c (ffffffff810d6abd)
Location: kernel/power/snapshot.c:1313
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
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
In kernel/power/snapshot.c (ffffffff810dd62c)
Location: kernel/power/snapshot.c:1335
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
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
In kernel/power/snapshot.c (ffffffff810dc70d)
Location: kernel/power/snapshot.c:1337
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
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
In kernel/power/snapshot.c (ffffffff810e492d)
Location: kernel/power/snapshot.c:1339
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
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
In kernel/power/snapshot.c (ffffffff810ed906)
Location: kernel/power/snapshot.c:1339
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
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
In kernel/power/snapshot.c (ffffffff810f8f71)
Location: kernel/power/snapshot.c:1340
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
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
In kernel/power/snapshot.c (ffffffff811015f1)
Location: kernel/power/snapshot.c:1347
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff8110da24)
Location: kernel/power/snapshot.c:1354
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void safe_copy_page(void *dst, struct page *s_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81118142)
Location: kernel/power/snapshot.c:1353
Inline: False
```
**Symbols:**

```
ffffffff81118142-ffffffff811181e4: safe_copy_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void safe_copy_page(void *dst, struct page *s_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81bdf57b)
Location: kernel/power/snapshot.c:1395
Inline: False
```
**Symbols:**

```
ffffffff81bdf57b-ffffffff81bdf67b: safe_copy_page (STB_LOCAL)
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
In kernel/power/snapshot.c (ffffffff81bd19b4)
Location: kernel/power/snapshot.c:1395
Inline: True
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
In kernel/power/snapshot.c (ffffffff81caa610)
Location: kernel/power/snapshot.c:1388
Inline: True
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
In kernel/power/snapshot.c (ffffffff81e5aa34)
Location: kernel/power/snapshot.c:1392
Inline: True
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
In kernel/power/snapshot.c (ffffffff81185f6a)
Location: kernel/power/snapshot.c:1392
Inline: True
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
In kernel/power/snapshot.c (ffffffff8119714c)
Location: kernel/power/snapshot.c:1444
Inline: True
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
In kernel/power/snapshot.c (ffffffff811a5c55)
Location: kernel/power/snapshot.c:1460
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (c03c08b0)
Location: kernel/power/snapshot.c:1354
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
  - kernel/power/snapshot.c:swsusp_save
```
</details>
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81105c44)
Location: kernel/power/snapshot.c:1353
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810f6ee4)
Location: kernel/power/snapshot.c:1354
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81103ef4)
Location: kernel/power/snapshot.c:1354
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff8110f2e4)
Location: kernel/power/snapshot.c:1354
Inline: True
Inline callers:
  - kernel/power/snapshot.c:swsusp_save
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
