# Function: <code>clone3_stack_valid</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109d226)
Location: kernel/fork.c:2582
Inline: True
Inline callers:
  - kernel/fork.c:clone3_args_valid
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
In kernel/fork.c (ffffffff810a76a9)
Location: kernel/fork.c:2701
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
In kernel/fork.c (ffffffff810a3489)
Location: kernel/fork.c:2680
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
In kernel/fork.c (ffffffff810a40d9)
Location: kernel/fork.c:2712
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
In kernel/fork.c (ffffffff810b58f9)
Location: kernel/fork.c:2805
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
In kernel/fork.c (ffffffff810cbd1b)
Location: kernel/fork.c:2882
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
In kernel/fork.c (ffffffff810e935b)
Location: kernel/fork.c:2914
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
In kernel/fork.c (ffffffff810f4f6b)
Location: kernel/fork.c:3147
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
In kernel/fork.c (ffffffff810fe30b)
Location: kernel/fork.c:3137
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
In kernel/fork.c (ffff8000100f522c)
Location: kernel/fork.c:2582
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
In kernel/fork.c (c0353af0)
Location: kernel/fork.c:2582
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
In kernel/fork.c (c00000000013b2e0)
Location: kernel/fork.c:2582
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
In kernel/fork.c (ffffffe0000c183a)
Location: kernel/fork.c:2582
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
In kernel/fork.c (ffffffff81096b46)
Location: kernel/fork.c:2582
Inline: True
Inline callers:
  - kernel/fork.c:clone3_args_valid
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
In kernel/fork.c (ffffffff810855c6)
Location: kernel/fork.c:2582
Inline: True
Inline callers:
  - kernel/fork.c:clone3_args_valid
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
In kernel/fork.c (ffffffff81096af6)
Location: kernel/fork.c:2582
Inline: True
Inline callers:
  - kernel/fork.c:clone3_args_valid
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
In kernel/fork.c (ffffffff8109e996)
Location: kernel/fork.c:2582
Inline: True
Inline callers:
  - kernel/fork.c:clone3_args_valid
```
</details>
</li>
</ul>

## Differences
