# Function: <code>copy_clone_args_from_user</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
int copy_clone_args_from_user(struct kernel_clone_args *kargs, struct clone_args *uargs, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81096d60)
Location: kernel/fork.c:2541
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_clone3
  - kernel/fork.c:__x64_sys_clone3
```
**Symbols:**

```
ffffffff81096d60-ffffffff81096e8e: copy_clone_args_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int copy_clone_args_from_user(struct kernel_clone_args *kargs, struct clone_args *uargs, size_t usize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109d0f0)
Location: kernel/fork.c:2536
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_clone3
  - kernel/fork.c:__x64_sys_clone3
```
**Symbols:**

```
ffffffff8109d0f0-ffffffff8109d1e8: copy_clone_args_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int copy_clone_args_from_user(struct kernel_clone_args *kargs, struct clone_args *uargs, size_t usize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a3ea0)
Location: kernel/fork.c:2624
Inline: False
Direct callers:
  - kernel/fork.c:__do_sys_clone3
```
**Symbols:**

```
ffffffff810a3ea0-ffffffff810a411e: copy_clone_args_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int copy_clone_args_from_user(struct kernel_clone_args *kargs, struct clone_args *uargs, size_t usize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109f530)
Location: kernel/fork.c:2603
Inline: False
Direct callers:
  - kernel/fork.c:__do_sys_clone3
```
**Symbols:**

```
ffffffff8109f530-ffffffff8109f7ae: copy_clone_args_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int copy_clone_args_from_user(struct kernel_clone_args *kargs, struct clone_args *uargs, size_t usize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a0400)
Location: kernel/fork.c:2635
Inline: False
Direct callers:
  - kernel/fork.c:__do_sys_clone3
```
**Symbols:**

```
ffffffff810a0400-ffffffff810a067e: copy_clone_args_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int copy_clone_args_from_user(struct kernel_clone_args *kargs, struct clone_args *uargs, size_t usize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810b1810)
Location: kernel/fork.c:2728
Inline: False
Direct callers:
  - kernel/fork.c:__do_sys_clone3
```
**Symbols:**

```
ffffffff810b1810-ffffffff810b1a8e: copy_clone_args_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int copy_clone_args_from_user(struct kernel_clone_args *kargs, struct clone_args *uargs, size_t usize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810c7c30)
Location: kernel/fork.c:2805
Inline: False
Direct callers:
  - kernel/fork.c:__do_sys_clone3
```
**Symbols:**

```
ffffffff810c7c30-ffffffff810c7eb3: copy_clone_args_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int copy_clone_args_from_user(struct kernel_clone_args *kargs, struct clone_args *uargs, size_t usize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810e45d0)
Location: kernel/fork.c:2837
Inline: False
Direct callers:
  - kernel/fork.c:__do_sys_clone3
```
**Symbols:**

```
ffffffff810e45d0-ffffffff810e4853: copy_clone_args_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int copy_clone_args_from_user(struct kernel_clone_args *kargs, struct clone_args *uargs, size_t usize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810efc60)
Location: kernel/fork.c:3070
Inline: False
Direct callers:
  - kernel/fork.c:__do_sys_clone3
```
**Symbols:**

```
ffffffff810efc60-ffffffff810eff04: copy_clone_args_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int copy_clone_args_from_user(struct kernel_clone_args *kargs, struct clone_args *uargs, size_t usize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810f9070)
Location: kernel/fork.c:3060
Inline: False
Direct callers:
  - kernel/fork.c:__do_sys_clone3
```
**Symbols:**

```
ffffffff810f9070-ffffffff810f9314: copy_clone_args_from_user (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int copy_clone_args_from_user(struct kernel_clone_args *kargs, struct clone_args *uargs, size_t usize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffff8000100f2008)
Location: kernel/fork.c:2536
Inline: False
Direct callers:
  - kernel/fork.c:__arm64_sys_clone3
```
**Symbols:**

```
ffff8000100f2008-ffff8000100f221c: copy_clone_args_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int copy_clone_args_from_user(struct kernel_clone_args *kargs, struct clone_args *uargs, size_t usize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c0350854)
Location: kernel/fork.c:2536
Inline: False
Direct callers:
  - kernel/fork.c:__se_sys_clone3
```
**Symbols:**

```
c0350854-c03509a0: copy_clone_args_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int copy_clone_args_from_user(struct kernel_clone_args *kargs, struct clone_args *uargs, size_t usize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c000000000137020)
Location: kernel/fork.c:2536
Inline: False
Direct callers:
  - kernel/fork.c:__se_sys_clone3
```
**Symbols:**

```
c000000000137020-c000000000137198: copy_clone_args_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int copy_clone_args_from_user(struct kernel_clone_args *kargs, struct clone_args *uargs, size_t usize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffe0000bea80)
Location: kernel/fork.c:2536
Inline: False
Direct callers:
  - kernel/fork.c:__se_sys_clone3
```
**Symbols:**

```
ffffffe0000bea80-ffffffe0000beb50: copy_clone_args_from_user (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int copy_clone_args_from_user(struct kernel_clone_args *kargs, struct clone_args *uargs, size_t usize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81096a10)
Location: kernel/fork.c:2536
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_clone3
  - kernel/fork.c:__x64_sys_clone3
```
**Symbols:**

```
ffffffff81096a10-ffffffff81096b08: copy_clone_args_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int copy_clone_args_from_user(struct kernel_clone_args *kargs, struct clone_args *uargs, size_t usize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81085490)
Location: kernel/fork.c:2536
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_clone3
  - kernel/fork.c:__x64_sys_clone3
```
**Symbols:**

```
ffffffff81085490-ffffffff81085588: copy_clone_args_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int copy_clone_args_from_user(struct kernel_clone_args *kargs, struct clone_args *uargs, size_t usize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810969c0)
Location: kernel/fork.c:2536
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_clone3
  - kernel/fork.c:__x64_sys_clone3
```
**Symbols:**

```
ffffffff810969c0-ffffffff81096ab8: copy_clone_args_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int copy_clone_args_from_user(struct kernel_clone_args *kargs, struct clone_args *uargs, size_t usize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109e860)
Location: kernel/fork.c:2536
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_clone3
  - kernel/fork.c:__x64_sys_clone3
```
**Symbols:**

```
ffffffff8109e860-ffffffff8109e958: copy_clone_args_from_user (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>size_t usize</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t size</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
