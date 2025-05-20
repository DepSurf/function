# Function: <code>__se_compat_sys_old_select</code>

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
In fs/select.c (ffffffff812b3215)
Location: fs/select.c:1298
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
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
In fs/select.c (ffffffff812c82d5)
Location: fs/select.c:1310
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
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
In fs/select.c (ffffffff812e4e45)
Location: fs/select.c:1283
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
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
In fs/select.c (ffffffff812f6865)
Location: fs/select.c:1283
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
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
In fs/select.c (ffffffff8132e795)
Location: fs/select.c:1293
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
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
In fs/select.c (ffffffff8133a025)
Location: fs/select.c:1299
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
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
In fs/select.c (ffffffff813405d5)
Location: fs/select.c:1299
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
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
In fs/select.c (ffffffff8138dfa5)
Location: fs/select.c:1302
Inline: True
Inline callers:
  - fs/select.c:__x64_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
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
In fs/select.c (ffffffff8140f294)
Location: fs/select.c:1303
Inline: True
Inline callers:
  - fs/select.c:__ia32_compat_sys_old_select
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
In fs/select.c (ffffffff81499e64)
Location: fs/select.c:1303
Inline: True
Inline callers:
  - fs/select.c:__ia32_compat_sys_old_select
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
In fs/select.c (ffffffff814cef34)
Location: fs/select.c:1303
Inline: True
Inline callers:
  - fs/select.c:__ia32_compat_sys_old_select
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
In fs/select.c (ffffffff81501874)
Location: fs/select.c:1303
Inline: True
Inline callers:
  - fs/select.c:__ia32_compat_sys_old_select
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
In fs/select.c (ffff8000103a3acc)
Location: fs/select.c:1283
Inline: True
Inline callers:
  - fs/select.c:__arm64_compat_sys_old_select
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __se_compat_sys_old_select(long int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (c00000000049d980)
Location: fs/select.c:1283
Inline: False
```
**Symbols:**

```
c00000000049d980-c00000000049da10: __se_compat_sys_old_select (STB_GLOBAL)
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
In fs/select.c (ffffffff812eee45)
Location: fs/select.c:1283
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
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
In fs/select.c (ffffffff812dfa75)
Location: fs/select.c:1283
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
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
In fs/select.c (ffffffff812ecc55)
Location: fs/select.c:1283
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
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
In fs/select.c (ffffffff812fdc55)
Location: fs/select.c:1283
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_old_select
  - fs/select.c:__ia32_compat_sys_old_select
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
