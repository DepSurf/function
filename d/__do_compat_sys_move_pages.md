# Function: <code>__do_compat_sys_move_pages</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81272226)
Location: mm/migrate.c:1796
Inline: True
Inline callers:
  - mm/migrate.c:__x32_compat_sys_move_pages
  - mm/migrate.c:__ia32_compat_sys_move_pages
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
In mm/migrate.c (ffffffff81286836)
Location: mm/migrate.c:1829
Inline: True
Inline callers:
  - mm/migrate.c:__x32_compat_sys_move_pages
  - mm/migrate.c:__ia32_compat_sys_move_pages
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
In mm/migrate.c (ffffffff812a0e01)
Location: mm/migrate.c:1824
Inline: True
Inline callers:
  - mm/migrate.c:__x32_compat_sys_move_pages
  - mm/migrate.c:__ia32_compat_sys_move_pages
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
In mm/migrate.c (ffffffff812b2211)
Location: mm/migrate.c:1857
Inline: True
Inline callers:
  - mm/migrate.c:__x32_compat_sys_move_pages
  - mm/migrate.c:__ia32_compat_sys_move_pages
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
In mm/migrate.c (ffffffff812e77b1)
Location: mm/migrate.c:1864
Inline: True
Inline callers:
  - mm/migrate.c:__x32_compat_sys_move_pages
  - mm/migrate.c:__ia32_compat_sys_move_pages
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
In mm/migrate.c (ffffffff812f2b71)
Location: mm/migrate.c:2000
Inline: True
Inline callers:
  - mm/migrate.c:__x32_compat_sys_move_pages
  - mm/migrate.c:__ia32_compat_sys_move_pages
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
In mm/migrate.c (ffffffff812f8f21)
Location: mm/migrate.c:1983
Inline: True
Inline callers:
  - mm/migrate.c:__x32_compat_sys_move_pages
  - mm/migrate.c:__ia32_compat_sys_move_pages
```
</details>
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffff8000103527f8)
Location: mm/migrate.c:1857
Inline: True
Inline callers:
  - mm/migrate.c:__arm64_compat_sys_move_pages
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (c000000000439288)
Location: mm/migrate.c:1857
Inline: True
Inline callers:
  - mm/migrate.c:__se_compat_sys_move_pages
```
</details>
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
In mm/migrate.c (ffffffff812aa7f1)
Location: mm/migrate.c:1857
Inline: True
Inline callers:
  - mm/migrate.c:__x32_compat_sys_move_pages
  - mm/migrate.c:__ia32_compat_sys_move_pages
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
In mm/migrate.c (ffffffff8129c151)
Location: mm/migrate.c:1857
Inline: True
Inline callers:
  - mm/migrate.c:__x32_compat_sys_move_pages
  - mm/migrate.c:__ia32_compat_sys_move_pages
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
In mm/migrate.c (ffffffff812a8601)
Location: mm/migrate.c:1857
Inline: True
Inline callers:
  - mm/migrate.c:__x32_compat_sys_move_pages
  - mm/migrate.c:__ia32_compat_sys_move_pages
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
In mm/migrate.c (ffffffff812b8921)
Location: mm/migrate.c:1857
Inline: True
Inline callers:
  - mm/migrate.c:__x32_compat_sys_move_pages
  - mm/migrate.c:__ia32_compat_sys_move_pages
```
</details>
</li>
</ul>

## Differences
