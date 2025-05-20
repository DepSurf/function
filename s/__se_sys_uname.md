# Function: <code>__se_sys_uname</code>

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
In kernel/sys.c (ffffffff810a5bd5)
Location: kernel/sys.c:1274
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_uname
  - kernel/sys.c:__x64_sys_uname
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
In kernel/sys.c (ffffffff810ae8d5)
Location: kernel/sys.c:1275
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_uname
  - kernel/sys.c:__x64_sys_uname
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
In kernel/sys.c (ffffffff810b32d5)
Location: kernel/sys.c:1275
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_uname
  - kernel/sys.c:__x64_sys_uname
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
In kernel/sys.c (ffffffff810b98c5)
Location: kernel/sys.c:1275
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_uname
  - kernel/sys.c:__x64_sys_uname
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
In kernel/sys.c (ffffffff810c1605)
Location: kernel/sys.c:1289
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_uname
  - kernel/sys.c:__x64_sys_uname
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
In kernel/sys.c (ffffffff810bc775)
Location: kernel/sys.c:1290
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_uname
  - kernel/sys.c:__x64_sys_uname
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
In kernel/sys.c (ffffffff810bdff5)
Location: kernel/sys.c:1307
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_uname
  - kernel/sys.c:__x64_sys_uname
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
In kernel/sys.c (ffffffff810d0b45)
Location: kernel/sys.c:1316
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_uname
  - kernel/sys.c:__x64_sys_uname
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
In kernel/sys.c (ffffffff810e8525)
Location: kernel/sys.c:1323
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_uname
  - kernel/sys.c:__x64_sys_uname
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
In kernel/sys.c (ffffffff81109305)
Location: kernel/sys.c:1324
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_uname
  - kernel/sys.c:__x64_sys_uname
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
In kernel/sys.c (ffffffff81115615)
Location: kernel/sys.c:1342
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_uname
  - kernel/sys.c:__x64_sys_uname
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
In kernel/sys.c (ffffffff8111f005)
Location: kernel/sys.c:1342
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_uname
  - kernel/sys.c:__x64_sys_uname
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
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __se_sys_uname(long int name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (c00000000015d9c0)
Location: kernel/sys.c:1275
Inline: False
```
**Symbols:**

```
c00000000015d9c0-c00000000015d9d4: __se_sys_uname (STB_GLOBAL)
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
In kernel/sys.c (ffffffff810b3c35)
Location: kernel/sys.c:1275
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_uname
  - kernel/sys.c:__x64_sys_uname
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
In kernel/sys.c (ffffffff810a2565)
Location: kernel/sys.c:1275
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_uname
  - kernel/sys.c:__x64_sys_uname
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
In kernel/sys.c (ffffffff810b3195)
Location: kernel/sys.c:1275
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_uname
  - kernel/sys.c:__x64_sys_uname
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
In kernel/sys.c (ffffffff810bbbb5)
Location: kernel/sys.c:1275
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_uname
  - kernel/sys.c:__x64_sys_uname
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
