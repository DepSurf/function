# Function: <code>__se_sys_clone</code>

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
In kernel/fork.c (ffffffff8108dc95)
Location: kernel/fork.c:2233
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_clone
  - kernel/fork.c:__x64_sys_clone
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
In kernel/fork.c (ffffffff81095f25)
Location: kernel/fork.c:2338
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_clone
  - kernel/fork.c:__x64_sys_clone
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
In kernel/fork.c (ffffffff8109a28d)
Location: kernel/fork.c:2517
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_clone
  - kernel/fork.c:__x64_sys_clone
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
In kernel/fork.c (ffffffff810a085d)
Location: kernel/fork.c:2502
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_clone
  - kernel/fork.c:__x64_sys_clone
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
In kernel/fork.c (ffffffff810a7825)
Location: kernel/fork.c:2590
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_clone
  - kernel/fork.c:__x64_sys_clone
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
In kernel/fork.c (ffffffff810a33c5)
Location: kernel/fork.c:2581
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_clone
  - kernel/fork.c:__x64_sys_clone
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
In kernel/fork.c (ffffffff810a4015)
Location: kernel/fork.c:2613
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_clone
  - kernel/fork.c:__x64_sys_clone
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
In kernel/fork.c (ffffffff810b5835)
Location: kernel/fork.c:2706
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_clone
  - kernel/fork.c:__x64_sys_clone
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
In kernel/fork.c (ffffffff810cbc15)
Location: kernel/fork.c:2783
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_clone
  - kernel/fork.c:__x64_sys_clone
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
In kernel/fork.c (ffffffff810e9245)
Location: kernel/fork.c:2815
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_clone
  - kernel/fork.c:__x64_sys_clone
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
In kernel/fork.c (ffffffff810f4e55)
Location: kernel/fork.c:3048
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_clone
  - kernel/fork.c:__x64_sys_clone
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
In kernel/fork.c (ffffffff810fe1f5)
Location: kernel/fork.c:3038
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_clone
  - kernel/fork.c:__x64_sys_clone
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
In kernel/fork.c (ffff8000100f52dc)
Location: kernel/fork.c:2486
Inline: True
Inline callers:
  - kernel/fork.c:__arm64_sys_clone
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __se_sys_clone(long int clone_flags, long int newsp, long int parent_tidptr, long int tls, long int child_tidptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c03539a8)
Location: kernel/fork.c:2486
Inline: False
```
**Symbols:**

```
c03539a8-c0353a4c: __se_sys_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __se_sys_clone(long int clone_flags, long int newsp, long int parent_tidptr, long int tls, long int child_tidptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c00000000013b350)
Location: kernel/fork.c:2486
Inline: False
```
**Symbols:**

```
c00000000013b350-c00000000013b408: __se_sys_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __se_sys_clone(long int clone_flags, long int newsp, long int parent_tidptr, long int tls, long int child_tidptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffe0000c176c)
Location: kernel/fork.c:2486
Inline: False
```
**Symbols:**

```
ffffffe0000c176c-ffffffe0000c17e8: __se_sys_clone (STB_GLOBAL)
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
In kernel/fork.c (ffffffff8109a17d)
Location: kernel/fork.c:2502
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_clone
  - kernel/fork.c:__x64_sys_clone
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
In kernel/fork.c (ffffffff81088bbd)
Location: kernel/fork.c:2502
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_clone
  - kernel/fork.c:__x64_sys_clone
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
In kernel/fork.c (ffffffff8109a12d)
Location: kernel/fork.c:2502
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_clone
  - kernel/fork.c:__x64_sys_clone
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
In kernel/fork.c (ffffffff810a1dad)
Location: kernel/fork.c:2502
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_clone
  - kernel/fork.c:__x64_sys_clone
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
