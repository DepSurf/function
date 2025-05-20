# Function: <code>__do_sys_clone</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_sys_clone(long unsigned int clone_flags, long unsigned int newsp, int *parent_tidptr, int *child_tidptr, long unsigned int tls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a7760)
Location: kernel/fork.c:2590
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_clone
  - kernel/fork.c:__x64_sys_clone
```
**Symbols:**

```
ffffffff810a7760-ffffffff810a77e6: __do_sys_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_sys_clone(long unsigned int clone_flags, long unsigned int newsp, int *parent_tidptr, int *child_tidptr, long unsigned int tls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a3310)
Location: kernel/fork.c:2581
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_clone
  - kernel/fork.c:__x64_sys_clone
```
**Symbols:**

```
ffffffff810a3310-ffffffff810a3385: __do_sys_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_sys_clone(long unsigned int clone_flags, long unsigned int newsp, int *parent_tidptr, int *child_tidptr, long unsigned int tls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a3f60)
Location: kernel/fork.c:2613
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_clone
  - kernel/fork.c:__x64_sys_clone
```
**Symbols:**

```
ffffffff810a3f60-ffffffff810a3fd5: __do_sys_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_sys_clone(long unsigned int clone_flags, long unsigned int newsp, int *parent_tidptr, int *child_tidptr, long unsigned int tls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810b5780)
Location: kernel/fork.c:2706
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_clone
  - kernel/fork.c:__x64_sys_clone
```
**Symbols:**

```
ffffffff810b5780-ffffffff810b57f5: __do_sys_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_sys_clone(long unsigned int clone_flags, long unsigned int newsp, int *parent_tidptr, int *child_tidptr, long unsigned int tls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810cbb20)
Location: kernel/fork.c:2783
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_clone
  - kernel/fork.c:__x64_sys_clone
```
**Symbols:**

```
ffffffff810cbb20-ffffffff810cbbc3: __do_sys_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_sys_clone(long unsigned int clone_flags, long unsigned int newsp, int *parent_tidptr, int *child_tidptr, long unsigned int tls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810e9130)
Location: kernel/fork.c:2815
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_clone
  - kernel/fork.c:__x64_sys_clone
```
**Symbols:**

```
ffffffff810e9130-ffffffff810e91d3: __do_sys_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_sys_clone(long unsigned int clone_flags, long unsigned int newsp, int *parent_tidptr, int *child_tidptr, long unsigned int tls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810f4d50)
Location: kernel/fork.c:3048
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_clone
  - kernel/fork.c:__x64_sys_clone
```
**Symbols:**

```
ffffffff810f4d50-ffffffff810f4de3: __do_sys_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_sys_clone(long unsigned int clone_flags, long unsigned int newsp, int *parent_tidptr, int *child_tidptr, long unsigned int tls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810fe0f0)
Location: kernel/fork.c:3038
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_clone
  - kernel/fork.c:__x64_sys_clone
```
**Symbols:**

```
ffffffff810fe0f0-ffffffff810fe183: __do_sys_clone (STB_LOCAL)
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
In kernel/fork.c (ffff8000100f52f4)
Location: kernel/fork.c:2486
Inline: True
Inline callers:
  - kernel/fork.c:__arm64_sys_clone
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
In kernel/fork.c (c03539ec)
Location: kernel/fork.c:2486
Inline: True
Inline callers:
  - kernel/fork.c:__se_sys_clone
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c00000000013b380)
Location: kernel/fork.c:2486
Inline: True
Inline callers:
  - kernel/fork.c:__se_sys_clone
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffe0000c1792)
Location: kernel/fork.c:2486
Inline: True
Inline callers:
  - kernel/fork.c:__se_sys_clone
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
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
