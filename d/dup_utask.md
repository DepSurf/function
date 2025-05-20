# Function: <code>dup_utask</code>

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
In kernel/events/uprobes.c (ffffffff81188918)
Location: kernel/events/uprobes.c:1431
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_copy_process
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
In kernel/events/uprobes.c (ffffffff8119afe8)
Location: kernel/events/uprobes.c:1436
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_copy_process
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
In kernel/events/uprobes.c (ffffffff811aa9f8)
Location: kernel/events/uprobes.c:1437
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_copy_process
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
In kernel/events/uprobes.c (ffffffff811b1f38)
Location: kernel/events/uprobes.c:1443
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_copy_process
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
In kernel/events/uprobes.c (ffffffff811c5b48)
Location: kernel/events/uprobes.c:1443
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_copy_process
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
In kernel/events/uprobes.c (ffffffff811e6068)
Location: kernel/events/uprobes.c:1443
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_copy_process
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
In kernel/events/uprobes.c (ffffffff811f6bb8)
Location: kernel/events/uprobes.c:1713
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_copy_process
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
In kernel/events/uprobes.c (ffffffff8120e97c)
Location: kernel/events/uprobes.c:1701
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_copy_process
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
In kernel/events/uprobes.c (ffffffff8121bfbc)
Location: kernel/events/uprobes.c:1753
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_copy_process
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dup_utask(struct task_struct *t, struct uprobe_task *o_utask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81245e20)
Location: kernel/events/uprobes.c:1752
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_copy_process
```
**Symbols:**

```
ffffffff81245e20-ffffffff81245f39: dup_utask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dup_utask(struct task_struct *t, struct uprobe_task *o_utask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81250490)
Location: kernel/events/uprobes.c:1752
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_copy_process
```
**Symbols:**

```
ffffffff81250490-ffffffff812505a9: dup_utask (STB_LOCAL)
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
In kernel/events/uprobes.c (ffffffff81257060)
Location: kernel/events/uprobes.c:1750
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_copy_process
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
In kernel/events/uprobes.c (ffffffff81292df0)
Location: kernel/events/uprobes.c:1751
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_copy_process
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
In kernel/events/uprobes.c (ffffffff812e8840)
Location: kernel/events/uprobes.c:1746
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_copy_process
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
In kernel/events/uprobes.c (ffffffff81352520)
Location: kernel/events/uprobes.c:1750
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_copy_process
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
In kernel/events/uprobes.c (ffffffff81383730)
Location: kernel/events/uprobes.c:1747
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_copy_process
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
In kernel/events/uprobes.c (ffffffff813acb30)
Location: kernel/events/uprobes.c:1747
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_copy_process
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
In kernel/events/uprobes.c (ffff8000102a7904)
Location: kernel/events/uprobes.c:1753
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_copy_process
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
In kernel/events/uprobes.c (c04d6a1c)
Location: kernel/events/uprobes.c:1753
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_copy_process
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
In kernel/events/uprobes.c (c00000000035aef8)
Location: kernel/events/uprobes.c:1753
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_copy_process
```
</details>
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
In kernel/events/uprobes.c (ffffffff8121460c)
Location: kernel/events/uprobes.c:1753
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_copy_process
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
In kernel/events/uprobes.c (ffffffff8120737c)
Location: kernel/events/uprobes.c:1753
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_copy_process
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
In kernel/events/uprobes.c (ffffffff812123ac)
Location: kernel/events/uprobes.c:1753
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_copy_process
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
In kernel/events/uprobes.c (ffffffff8122132c)
Location: kernel/events/uprobes.c:1753
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_copy_process
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
