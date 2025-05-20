# Function: <code>clone3_args_valid</code>

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
In kernel/fork.c (ffffffff8109a213)
Location: kernel/fork.c:2599
Inline: True
Inline callers:
  - kernel/fork.c:__ia32_sys_clone3
  - kernel/fork.c:__x64_sys_clone3
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool clone3_args_valid(struct kernel_clone_args *kargs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109d1f0)
Location: kernel/fork.c:2602
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_clone3
  - kernel/fork.c:__x64_sys_clone3
```
**Symbols:**

```
ffffffff8109d1f0-ffffffff8109d25f: clone3_args_valid (STB_LOCAL)
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
In kernel/fork.c (ffffffff810a7665)
Location: kernel/fork.c:2721
Inline: True
Inline callers:
  - kernel/fork.c:__do_sys_clone3
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
In kernel/fork.c (ffffffff810a3445)
Location: kernel/fork.c:2700
Inline: True
Inline callers:
  - kernel/fork.c:__do_sys_clone3
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
In kernel/fork.c (ffffffff810a4095)
Location: kernel/fork.c:2732
Inline: True
Inline callers:
  - kernel/fork.c:__do_sys_clone3
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
In kernel/fork.c (ffffffff810b58b5)
Location: kernel/fork.c:2825
Inline: True
Inline callers:
  - kernel/fork.c:__do_sys_clone3
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
In kernel/fork.c (ffffffff810cbcd5)
Location: kernel/fork.c:2902
Inline: True
Inline callers:
  - kernel/fork.c:__do_sys_clone3
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
In kernel/fork.c (ffffffff810e9315)
Location: kernel/fork.c:2934
Inline: True
Inline callers:
  - kernel/fork.c:__do_sys_clone3
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
In kernel/fork.c (ffffffff810f4f25)
Location: kernel/fork.c:3167
Inline: True
Inline callers:
  - kernel/fork.c:__do_sys_clone3
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
In kernel/fork.c (ffffffff810fe2c5)
Location: kernel/fork.c:3157
Inline: True
Inline callers:
  - kernel/fork.c:__do_sys_clone3
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
In kernel/fork.c (ffff8000100f5204)
Location: kernel/fork.c:2602
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
In kernel/fork.c (c0353ab0)
Location: kernel/fork.c:2602
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
In kernel/fork.c (c00000000013b2b0)
Location: kernel/fork.c:2602
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
In kernel/fork.c (ffffffe0000c1820)
Location: kernel/fork.c:2602
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
<summary>In <code>aws</code>: ✅</summary>

```c
bool clone3_args_valid(struct kernel_clone_args *kargs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81096b10)
Location: kernel/fork.c:2602
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_clone3
  - kernel/fork.c:__x64_sys_clone3
```
**Symbols:**

```
ffffffff81096b10-ffffffff81096b7f: clone3_args_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool clone3_args_valid(struct kernel_clone_args *kargs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81085590)
Location: kernel/fork.c:2602
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_clone3
  - kernel/fork.c:__x64_sys_clone3
```
**Symbols:**

```
ffffffff81085590-ffffffff810855ff: clone3_args_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool clone3_args_valid(struct kernel_clone_args *kargs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81096ac0)
Location: kernel/fork.c:2602
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_clone3
  - kernel/fork.c:__x64_sys_clone3
```
**Symbols:**

```
ffffffff81096ac0-ffffffff81096b2f: clone3_args_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool clone3_args_valid(struct kernel_clone_args *kargs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109e960)
Location: kernel/fork.c:2602
Inline: False
Direct callers:
  - kernel/fork.c:__ia32_sys_clone3
  - kernel/fork.c:__x64_sys_clone3
```
**Symbols:**

```
ffffffff8109e960-ffffffff8109e9cf: clone3_args_valid (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
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
