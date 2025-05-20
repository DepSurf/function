# Function: <code>__se_sys_clone3</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109a202)
Location: kernel/fork.c:2622
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_clone3
  - kernel/fork.c:__x64_sys_clone3
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
In kernel/fork.c (ffffffff810a07e2)
Location: kernel/fork.c:2639
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_clone3
  - kernel/fork.c:__x64_sys_clone3
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
In kernel/fork.c (ffffffff810a7745)
Location: kernel/fork.c:2760
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_clone3
  - kernel/fork.c:__x64_sys_clone3
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
In kernel/fork.c (ffffffff810a3535)
Location: kernel/fork.c:2739
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_clone3
  - kernel/fork.c:__x64_sys_clone3
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
In kernel/fork.c (ffffffff810a4165)
Location: kernel/fork.c:2771
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_clone3
  - kernel/fork.c:__x64_sys_clone3
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
In kernel/fork.c (ffffffff810b5985)
Location: kernel/fork.c:2864
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_clone3
  - kernel/fork.c:__x64_sys_clone3
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
In kernel/fork.c (ffffffff810cbdb5)
Location: kernel/fork.c:2941
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_clone3
  - kernel/fork.c:__x64_sys_clone3
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
In kernel/fork.c (ffffffff810e9415)
Location: kernel/fork.c:2973
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_clone3
  - kernel/fork.c:__x64_sys_clone3
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
In kernel/fork.c (ffffffff810f5015)
Location: kernel/fork.c:3206
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_clone3
  - kernel/fork.c:__x64_sys_clone3
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
In kernel/fork.c (ffffffff810fe3b5)
Location: kernel/fork.c:3196
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_clone3
  - kernel/fork.c:__x64_sys_clone3
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
In kernel/fork.c (ffff8000100f51d0)
Location: kernel/fork.c:2639
Inline: True
Inline callers:
  - kernel/fork.c:__arm64_sys_clone3
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __se_sys_clone3(long int uargs, long int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c0353a4c)
Location: kernel/fork.c:2639
Inline: False
```
**Symbols:**

```
c0353a4c-c0353b4c: __se_sys_clone3 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __se_sys_clone3(long int uargs, long int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c00000000013b240)
Location: kernel/fork.c:2639
Inline: False
```
**Symbols:**

```
c00000000013b240-c00000000013b348: __se_sys_clone3 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __se_sys_clone3(long int uargs, long int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffe0000c17e8)
Location: kernel/fork.c:2639
Inline: False
```
**Symbols:**

```
ffffffe0000c17e8-ffffffe0000c1880: __se_sys_clone3 (STB_GLOBAL)
```
</details>
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
In kernel/fork.c (ffffffff8109a102)
Location: kernel/fork.c:2639
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_clone3
  - kernel/fork.c:__x64_sys_clone3
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
In kernel/fork.c (ffffffff81088b42)
Location: kernel/fork.c:2639
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_clone3
  - kernel/fork.c:__x64_sys_clone3
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
In kernel/fork.c (ffffffff8109a0b2)
Location: kernel/fork.c:2639
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_clone3
  - kernel/fork.c:__x64_sys_clone3
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
In kernel/fork.c (ffffffff810a1d32)
Location: kernel/fork.c:2639
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_clone3
  - kernel/fork.c:__x64_sys_clone3
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
