# Function: <code>__do_sys_clone3</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_sys_clone3(struct clone_args *uargs, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a7610)
Location: kernel/fork.c:2760
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_clone3
  - kernel/fork.c:__x64_sys_clone3
```
**Symbols:**

```
ffffffff810a7610-ffffffff810a7712: __do_sys_clone3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_sys_clone3(struct clone_args *uargs, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a33f0)
Location: kernel/fork.c:2739
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_clone3
  - kernel/fork.c:__x64_sys_clone3
```
**Symbols:**

```
ffffffff810a33f0-ffffffff810a350d: __do_sys_clone3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_sys_clone3(struct clone_args *uargs, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a4040)
Location: kernel/fork.c:2771
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_clone3
  - kernel/fork.c:__x64_sys_clone3
```
**Symbols:**

```
ffffffff810a4040-ffffffff810a413c: __do_sys_clone3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_sys_clone3(struct clone_args *uargs, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810b5860)
Location: kernel/fork.c:2864
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_clone3
  - kernel/fork.c:__x64_sys_clone3
```
**Symbols:**

```
ffffffff810b5860-ffffffff810b595c: __do_sys_clone3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_sys_clone3(struct clone_args *uargs, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810cbc50)
Location: kernel/fork.c:2941
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_clone3
  - kernel/fork.c:__x64_sys_clone3
```
**Symbols:**

```
ffffffff810cbc50-ffffffff810cbd84: __do_sys_clone3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_sys_clone3(struct clone_args *uargs, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810e9290)
Location: kernel/fork.c:2973
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_clone3
  - kernel/fork.c:__x64_sys_clone3
```
**Symbols:**

```
ffffffff810e9290-ffffffff810e93c4: __do_sys_clone3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_sys_clone3(struct clone_args *uargs, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810f4ea0)
Location: kernel/fork.c:3206
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_clone3
  - kernel/fork.c:__x64_sys_clone3
```
**Symbols:**

```
ffffffff810f4ea0-ffffffff810f4fd0: __do_sys_clone3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_sys_clone3(struct clone_args *uargs, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810fe240)
Location: kernel/fork.c:3196
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_clone3
  - kernel/fork.c:__x64_sys_clone3
```
**Symbols:**

```
ffffffff810fe240-ffffffff810fe370: __do_sys_clone3 (STB_LOCAL)
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
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c0353a84)
Location: kernel/fork.c:2639
Inline: True
Inline callers:
  - kernel/fork.c:__se_sys_clone3
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
In kernel/fork.c (c00000000013b274)
Location: kernel/fork.c:2639
Inline: True
Inline callers:
  - kernel/fork.c:__se_sys_clone3
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
In kernel/fork.c (ffffffe0000c1802)
Location: kernel/fork.c:2639
Inline: True
Inline callers:
  - kernel/fork.c:__se_sys_clone3
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
