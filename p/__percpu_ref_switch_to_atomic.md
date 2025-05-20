# Function: <code>__percpu_ref_switch_to_atomic</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __percpu_ref_switch_to_atomic(struct percpu_ref *ref, percpu_ref_func_t *confirm_switch);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff813ff1c0)
Location: lib/percpu-refcount.c:161
Inline: True
Direct callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic
```
**Symbols:**

```
ffffffff813ff1c0-ffffffff813ff309: __percpu_ref_switch_to_atomic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __percpu_ref_switch_to_atomic(struct percpu_ref *ref, percpu_ref_func_t *confirm_switch);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff814468a0)
Location: lib/percpu-refcount.c:161
Inline: True
Direct callers:
  - lib/percpu-refcount.c:percpu_ref_kill_and_confirm
  - lib/percpu-refcount.c:percpu_ref_switch_to_atomic
```
**Symbols:**

```
ffffffff814468a0-ffffffff814469f0: __percpu_ref_switch_to_atomic (STB_LOCAL)
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
In lib/percpu-refcount.c (ffffffff81465049)
Location: lib/percpu-refcount.c:165
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
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
In lib/percpu-refcount.c (ffffffff8146a059)
Location: lib/percpu-refcount.c:165
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
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
In lib/percpu-refcount.c (ffffffff81496349)
Location: lib/percpu-refcount.c:165
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
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
In lib/percpu-refcount.c (ffffffff814cb5a9)
Location: lib/percpu-refcount.c:165
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
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
In lib/percpu-refcount.c (ffffffff814e02d9)
Location: lib/percpu-refcount.c:165
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
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
In lib/percpu-refcount.c (ffffffff8150c260)
Location: lib/percpu-refcount.c:172
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
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
In lib/percpu-refcount.c (ffffffff8152a0b0)
Location: lib/percpu-refcount.c:172
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
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
In lib/percpu-refcount.c (ffffffff8158d860)
Location: lib/percpu-refcount.c:173
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
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
In lib/percpu-refcount.c (ffffffff815aa4c3)
Location: lib/percpu-refcount.c:206
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
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
In lib/percpu-refcount.c (ffffffff815b50e3)
Location: lib/percpu-refcount.c:212
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
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
In lib/percpu-refcount.c (ffffffff8161b453)
Location: lib/percpu-refcount.c:212
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
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
In lib/percpu-refcount.c (ffffffff816e8c3f)
Location: lib/percpu-refcount.c:213
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
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
In lib/percpu-refcount.c (ffffffff817d8cc1)
Location: lib/percpu-refcount.c:213
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
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
In lib/percpu-refcount.c (ffffffff81817ca1)
Location: lib/percpu-refcount.c:213
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
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
In lib/percpu-refcount.c (ffffffff8185cfa1)
Location: lib/percpu-refcount.c:213
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
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
In lib/percpu-refcount.c (ffff800010635118)
Location: lib/percpu-refcount.c:172
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
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
In lib/percpu-refcount.c (c07db19c)
Location: lib/percpu-refcount.c:172
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
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
In lib/percpu-refcount.c (c0000000007da970)
Location: lib/percpu-refcount.c:172
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
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
In lib/percpu-refcount.c (ffffffe000462bde)
Location: lib/percpu-refcount.c:172
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
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
In lib/percpu-refcount.c (ffffffff81522690)
Location: lib/percpu-refcount.c:172
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
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
In lib/percpu-refcount.c (ffffffff8151297a)
Location: lib/percpu-refcount.c:172
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
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
In lib/percpu-refcount.c (ffffffff8151e720)
Location: lib/percpu-refcount.c:172
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
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
In lib/percpu-refcount.c (ffffffff81537fa2)
Location: lib/percpu-refcount.c:172
Inline: True
Inline callers:
  - lib/percpu-refcount.c:__percpu_ref_switch_mode
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
</ul>
