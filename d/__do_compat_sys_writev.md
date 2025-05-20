# Function: <code>__do_compat_sys_writev</code>

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
In fs/read_write.c (ffffffff81299645)
Location: fs/read_write.c:1327
Inline: True
Inline callers:
  - fs/read_write.c:__x32_compat_sys_writev
  - fs/read_write.c:__ia32_compat_sys_writev
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
In fs/read_write.c (ffffffff812ae4c5)
Location: fs/read_write.c:1324
Inline: True
Inline callers:
  - fs/read_write.c:__x32_compat_sys_writev
  - fs/read_write.c:__ia32_compat_sys_writev
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
In fs/read_write.c (ffffffff812cb165)
Location: fs/read_write.c:1349
Inline: True
Inline callers:
  - fs/read_write.c:__x32_compat_sys_writev
  - fs/read_write.c:__ia32_compat_sys_writev
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
In fs/read_write.c (ffffffff812dcb85)
Location: fs/read_write.c:1349
Inline: True
Inline callers:
  - fs/read_write.c:__x32_compat_sys_writev
  - fs/read_write.c:__ia32_compat_sys_writev
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
In fs/read_write.c (ffffffff81313a45)
Location: fs/read_write.c:1433
Inline: True
Inline callers:
  - fs/read_write.c:__x32_compat_sys_writev
  - fs/read_write.c:__ia32_compat_sys_writev
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
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
In fs/read_write.c (ffff8000103825b8)
Location: fs/read_write.c:1349
Inline: True
Inline callers:
  - fs/read_write.c:__arm64_compat_sys_writev
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
In fs/read_write.c (c000000000478d40)
Location: fs/read_write.c:1349
Inline: True
Inline callers:
  - fs/read_write.c:__se_compat_sys_writev
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
In fs/read_write.c (ffffffff812d5165)
Location: fs/read_write.c:1349
Inline: True
Inline callers:
  - fs/read_write.c:__x32_compat_sys_writev
  - fs/read_write.c:__ia32_compat_sys_writev
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
In fs/read_write.c (ffffffff812c5de5)
Location: fs/read_write.c:1349
Inline: True
Inline callers:
  - fs/read_write.c:__x32_compat_sys_writev
  - fs/read_write.c:__ia32_compat_sys_writev
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
In fs/read_write.c (ffffffff812d2f75)
Location: fs/read_write.c:1349
Inline: True
Inline callers:
  - fs/read_write.c:__x32_compat_sys_writev
  - fs/read_write.c:__ia32_compat_sys_writev
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
In fs/read_write.c (ffffffff812e3dd5)
Location: fs/read_write.c:1349
Inline: True
Inline callers:
  - fs/read_write.c:__x32_compat_sys_writev
  - fs/read_write.c:__ia32_compat_sys_writev
```
</details>
</li>
</ul>

## Differences
