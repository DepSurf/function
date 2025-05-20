# Function: <code>wait_for_vfork_done</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81080368)
Location: kernel/fork.c:830
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810821a1)
Location: kernel/fork.c:888
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81086c01)
Location: kernel/fork.c:1042
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8108394d)
Location: kernel/fork.c:1089
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8108a230)
Location: kernel/fork.c:1101
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8108da77)
Location: kernel/fork.c:1170
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
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
In kernel/fork.c (ffffffff81095d07)
Location: kernel/fork.c:1226
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
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
In kernel/fork.c (ffffffff81099f9d)
Location: kernel/fork.c:1243
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
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
In kernel/fork.c (ffffffff810a057d)
Location: kernel/fork.c:1258
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int wait_for_vfork_done(struct task_struct *child, struct completion *vfork);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a51b0)
Location: kernel/fork.c:1272
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
```
**Symbols:**

```
ffffffff810a51b0-ffffffff810a52a0: wait_for_vfork_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int wait_for_vfork_done(struct task_struct *child, struct completion *vfork);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a08d0)
Location: kernel/fork.c:1269
Inline: False
Direct callers:
  - kernel/fork.c:kernel_clone
```
**Symbols:**

```
ffffffff810a08d0-ffffffff810a09c0: wait_for_vfork_done (STB_LOCAL)
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
In kernel/fork.c (ffffffff810a3cba)
Location: kernel/fork.c:1275
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
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
In kernel/fork.c (ffffffff810b54d7)
Location: kernel/fork.c:1354
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
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
In kernel/fork.c (ffffffff810cb84a)
Location: kernel/fork.c:1426
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
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
In kernel/fork.c (ffffffff810e8e8e)
Location: kernel/fork.c:1450
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
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
In kernel/fork.c (ffffffff810f4aac)
Location: kernel/fork.c:1591
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
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
In kernel/fork.c (ffffffff810fde4c)
Location: kernel/fork.c:1587
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
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
In kernel/fork.c (ffff8000100f4e4c)
Location: kernel/fork.c:1258
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
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
In kernel/fork.c (c0353590)
Location: kernel/fork.c:1258
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
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
In kernel/fork.c (c00000000013af24)
Location: kernel/fork.c:1258
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
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
In kernel/fork.c (ffffffe0000c14dc)
Location: kernel/fork.c:1258
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
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
In kernel/fork.c (ffffffff81099e9d)
Location: kernel/fork.c:1258
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
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
In kernel/fork.c (ffffffff810888dd)
Location: kernel/fork.c:1258
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
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
In kernel/fork.c (ffffffff81099e4d)
Location: kernel/fork.c:1258
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
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
In kernel/fork.c (ffffffff810a1ab6)
Location: kernel/fork.c:1258
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
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
</ul>
