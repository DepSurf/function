# Function: <code>bug_at</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void bug_at(unsigned char *ip, int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/jump_label.c (ffffffff810338f0)
Location: arch/x86/kernel/jump_label.c:27
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_static
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_static
```
**Symbols:**

```
ffffffff810338f0-ffffffff8103393a: bug_at (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void bug_at(unsigned char *ip, int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/jump_label.c (ffffffff81032ab0)
Location: arch/x86/kernel/jump_label.c:28
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_static
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_static
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform
```
**Symbols:**

```
ffffffff81032ab0-ffffffff81032afa: bug_at (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void bug_at(unsigned char *ip, int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/jump_label.c (ffffffff81032730)
Location: arch/x86/kernel/jump_label.c:28
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_static
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_static
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform
```
**Symbols:**

```
ffffffff81032730-ffffffff8103277a: bug_at (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void bug_at(unsigned char *ip, int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/jump_label.c (ffffffff81030a80)
Location: arch/x86/kernel/jump_label.c:28
Inline: False
```
**Symbols:**

```
ffffffff81030a80-ffffffff81030aa3: bug_at (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void bug_at(unsigned char *ip, int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/jump_label.c (ffffffff81032c90)
Location: arch/x86/kernel/jump_label.c:29
Inline: False
```
**Symbols:**

```
ffffffff81032c90-ffffffff81032cb3: bug_at (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void bug_at(unsigned char *ip, int line);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/jump_label.c (ffffffff810341e8)
Location: arch/x86/kernel/jump_label.c:29
Inline: False
```
**Symbols:**

```
ffffffff810341e8-ffffffff8103420b: bug_at (STB_LOCAL)
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
In arch/x86/kernel/jump_label.c (ffffffff81a1fe27)
Location: arch/x86/kernel/jump_label.c:27
Inline: True
Inline callers:
  - arch/x86/kernel/jump_label.c:__jump_label_transform
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
In arch/x86/kernel/jump_label.c (ffffffff810372f4)
Location: arch/x86/kernel/jump_label.c:27
Inline: True
Inline callers:
  - arch/x86/kernel/jump_label.c:__jump_label_set_jump_code
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
In arch/x86/kernel/jump_label.c (ffffffff81037ac4)
Location: arch/x86/kernel/jump_label.c:27
Inline: True
Inline callers:
  - arch/x86/kernel/jump_label.c:__jump_label_set_jump_code
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
In arch/x86/kernel/jump_label.c (ffffffff81039a0d)
Location: arch/x86/kernel/jump_label.c:19
Inline: True
Inline callers:
  - arch/x86/kernel/jump_label.c:__jump_label_set_jump_code
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
In arch/x86/kernel/jump_label.c (ffffffff8103a23d)
Location: arch/x86/kernel/jump_label.c:19
Inline: True
Inline callers:
  - arch/x86/kernel/jump_label.c:__jump_label_set_jump_code
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
In arch/x86/kernel/jump_label.c (ffffffff8103bc9e)
Location: arch/x86/kernel/jump_label.c:19
Inline: True
Inline callers:
  - arch/x86/kernel/jump_label.c:__jump_label_set_jump_code
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In <code>ppc64el</code>: Absent ⚠️
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
In arch/x86/kernel/jump_label.c (ffffffff81037c24)
Location: arch/x86/kernel/jump_label.c:27
Inline: True
Inline callers:
  - arch/x86/kernel/jump_label.c:__jump_label_set_jump_code
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
In arch/x86/kernel/jump_label.c (ffffffff81027604)
Location: arch/x86/kernel/jump_label.c:27
Inline: True
Inline callers:
  - arch/x86/kernel/jump_label.c:__jump_label_set_jump_code
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
In arch/x86/kernel/jump_label.c (ffffffff81037a84)
Location: arch/x86/kernel/jump_label.c:27
Inline: True
Inline callers:
  - arch/x86/kernel/jump_label.c:__jump_label_set_jump_code
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
In arch/x86/kernel/jump_label.c (ffffffff81038a84)
Location: arch/x86/kernel/jump_label.c:27
Inline: True
Inline callers:
  - arch/x86/kernel/jump_label.c:__jump_label_set_jump_code
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
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
