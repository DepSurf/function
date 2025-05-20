# Function: <code>__do_compat_sys_select</code>

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
In fs/select.c (ffffffff812b3155)
Location: fs/select.c:1283
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_select
  - fs/select.c:__ia32_compat_sys_select
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
In fs/select.c (ffffffff812c8215)
Location: fs/select.c:1295
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_select
  - fs/select.c:__ia32_compat_sys_select
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
In fs/select.c (ffffffff812e4d85)
Location: fs/select.c:1268
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_select
  - fs/select.c:__ia32_compat_sys_select
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
In fs/select.c (ffffffff812f67a5)
Location: fs/select.c:1268
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_select
  - fs/select.c:__ia32_compat_sys_select
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
In fs/select.c (ffffffff8132e6d5)
Location: fs/select.c:1278
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_select
  - fs/select.c:__ia32_compat_sys_select
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
In fs/select.c (ffffffff81339f65)
Location: fs/select.c:1284
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_select
  - fs/select.c:__ia32_compat_sys_select
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
In fs/select.c (ffffffff81340515)
Location: fs/select.c:1284
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_select
  - fs/select.c:__ia32_compat_sys_select
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
In fs/select.c (ffffffff8138dee5)
Location: fs/select.c:1287
Inline: True
Inline callers:
  - fs/select.c:__x64_compat_sys_select
  - fs/select.c:__ia32_compat_sys_select
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
In fs/select.c (ffffffff8140f235)
Location: fs/select.c:1288
Inline: True
Inline callers:
  - fs/select.c:__ia32_compat_sys_select
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
In fs/select.c (ffffffff81499df5)
Location: fs/select.c:1288
Inline: True
Inline callers:
  - fs/select.c:__ia32_compat_sys_select
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
In fs/select.c (ffffffff814ceec5)
Location: fs/select.c:1288
Inline: True
Inline callers:
  - fs/select.c:__ia32_compat_sys_select
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
In fs/select.c (ffffffff81501805)
Location: fs/select.c:1288
Inline: True
Inline callers:
  - fs/select.c:__ia32_compat_sys_select
```
</details>
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
In fs/select.c (ffff8000103a3a78)
Location: fs/select.c:1268
Inline: True
Inline callers:
  - fs/select.c:__arm64_compat_sys_select
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
In fs/select.c (c00000000049d95c)
Location: fs/select.c:1268
Inline: True
Inline callers:
  - fs/select.c:__se_compat_sys_select
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
In fs/select.c (ffffffff812eed85)
Location: fs/select.c:1268
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_select
  - fs/select.c:__ia32_compat_sys_select
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
In fs/select.c (ffffffff812df9b5)
Location: fs/select.c:1268
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_select
  - fs/select.c:__ia32_compat_sys_select
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
In fs/select.c (ffffffff812ecb95)
Location: fs/select.c:1268
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_select
  - fs/select.c:__ia32_compat_sys_select
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
In fs/select.c (ffffffff812fdb95)
Location: fs/select.c:1268
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_select
  - fs/select.c:__ia32_compat_sys_select
```
</details>
</li>
</ul>

## Differences
