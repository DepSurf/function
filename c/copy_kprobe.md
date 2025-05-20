# Function: <code>copy_kprobe</code>

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
In kernel/kprobes.c (ffffffff8112c9a5)
Location: kernel/kprobes.c:337
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
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
In kernel/kprobes.c (ffffffff81134ba5)
Location: kernel/kprobes.c:337
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
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
In kernel/kprobes.c (ffffffff8113e925)
Location: kernel/kprobes.c:337
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
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
In kernel/kprobes.c (0)
Location: kernel/kprobes.c:369
Inline: True
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
In kernel/kprobes.c (0)
Location: kernel/kprobes.c:369
Inline: True
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
In kernel/kprobes.c (0)
Location: kernel/kprobes.c:369
Inline: True
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
In kernel/kprobes.c (0)
Location: kernel/kprobes.c:369
Inline: True
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
In kernel/kprobes.c (0)
Location: kernel/kprobes.c:356
Inline: True
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
In kernel/kprobes.c (0)
Location: kernel/kprobes.c:356
Inline: True
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
In kernel/kprobes.c (0)
Location: kernel/kprobes.c:362
Inline: True
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
In kernel/kprobes.c (0)
Location: kernel/kprobes.c:388
Inline: True
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
In kernel/kprobes.c (ffffffff8119414d)
Location: kernel/kprobes.c:389
Inline: True
Inline callers:
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:init_aggr_kprobe
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
In kernel/kprobes.c (ffffffff811bcfe4)
Location: kernel/kprobes.c:399
Inline: True
Inline callers:
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:init_aggr_kprobe
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
In kernel/kprobes.c (ffffffff811f0ce9)
Location: kernel/kprobes.c:408
Inline: True
Inline callers:
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:init_aggr_kprobe
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void copy_kprobe(struct kprobe *ap, struct kprobe *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81235d50)
Location: kernel/kprobes.c:408
Inline: False
Direct callers:
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:init_aggr_kprobe
```
**Symbols:**

```
ffffffff81235d50-ffffffff81235d86: copy_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void copy_kprobe(struct kprobe *ap, struct kprobe *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8124cb70)
Location: kernel/kprobes.c:408
Inline: False
Direct callers:
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:init_aggr_kprobe
```
**Symbols:**

```
ffffffff8124cb70-ffffffff8124cba6: copy_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void copy_kprobe(struct kprobe *ap, struct kprobe *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81266a70)
Location: kernel/kprobes.c:408
Inline: False
Direct callers:
  - kernel/kprobes.c:register_aggr_kprobe
  - kernel/kprobes.c:init_aggr_kprobe
```
**Symbols:**

```
ffffffff81266a70-ffffffff81266aa6: copy_kprobe (STB_LOCAL)
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
In kernel/kprobes.c (ffff8000101f8e30)
Location: kernel/kprobes.c:356
Inline: True
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
In kernel/kprobes.c (c04383cc)
Location: kernel/kprobes.c:356
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
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
In kernel/kprobes.c (c00000000026f120)
Location: kernel/kprobes.c:356
Inline: True
Inline callers:
  - kernel/kprobes.c:init_aggr_kprobe
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
In kernel/kprobes.c (0)
Location: kernel/kprobes.c:356
Inline: True
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
In kernel/kprobes.c (0)
Location: kernel/kprobes.c:356
Inline: True
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
In kernel/kprobes.c (0)
Location: kernel/kprobes.c:356
Inline: True
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
In kernel/kprobes.c (0)
Location: kernel/kprobes.c:356
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
