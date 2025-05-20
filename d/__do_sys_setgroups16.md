# Function: <code>__do_sys_setgroups16</code>

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
In kernel/uid16.c (ffffffff8112d6d8)
Location: kernel/uid16.c:177
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
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
In kernel/uid16.c (ffffffff81138fc8)
Location: kernel/uid16.c:177
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
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
In kernel/uid16.c (ffffffff811441ba)
Location: kernel/uid16.c:177
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
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
In kernel/uid16.c (ffffffff8114fc9a)
Location: kernel/uid16.c:177
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
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
In kernel/uid16.c (ffffffff8116047a)
Location: kernel/uid16.c:177
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
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
In kernel/uid16.c (ffffffff8115c40a)
Location: kernel/uid16.c:177
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
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
In kernel/uid16.c (ffffffff8115d62a)
Location: kernel/uid16.c:177
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
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
In kernel/uid16.c (ffffffff8118292a)
Location: kernel/uid16.c:177
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
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
In kernel/uid16.c (ffffffff811b91fa)
Location: kernel/uid16.c:177
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
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
In kernel/uid16.c (ffffffff811fa73a)
Location: kernel/uid16.c:177
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
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
In kernel/uid16.c (ffffffff8120fada)
Location: kernel/uid16.c:177
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_sys_setgroups16(int gidsetsize, old_gid_t *grouplist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff812276b0)
Location: kernel/uid16.c:177
Inline: False
Direct callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
**Symbols:**

```
ffffffff812276b0-ffffffff812277d4: __do_sys_setgroups16 (STB_LOCAL)
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
In kernel/uid16.c (ffff8000101be060)
Location: kernel/uid16.c:177
Inline: True
Inline callers:
  - kernel/uid16.c:__arm64_sys_setgroups16
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (c040640c)
Location: kernel/uid16.c:177
Inline: True
Inline callers:
  - kernel/uid16.c:__se_sys_setgroups16
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
In kernel/uid16.c (ffffffff811482ba)
Location: kernel/uid16.c:177
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
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
In kernel/uid16.c (ffffffff8113b56a)
Location: kernel/uid16.c:177
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
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
In kernel/uid16.c (ffffffff8114616a)
Location: kernel/uid16.c:177
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
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
In kernel/uid16.c (ffffffff81152d7a)
Location: kernel/uid16.c:177
Inline: True
Inline callers:
  - kernel/uid16.c:__ia32_sys_setgroups16
  - kernel/uid16.c:__x64_sys_setgroups16
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
