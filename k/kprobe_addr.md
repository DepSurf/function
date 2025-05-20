# Function: <code>kprobe_addr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
kprobe_opcode_t *kprobe_addr(struct kprobe *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8112cf90)
Location: kernel/kprobes.c:1359
Inline: False
```
**Symbols:**

```
ffffffff8112cf90-ffffffff8112cfe2: kprobe_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
kprobe_opcode_t *kprobe_addr(struct kprobe *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81135140)
Location: kernel/kprobes.c:1359
Inline: False
```
**Symbols:**

```
ffffffff81135140-ffffffff81135192: kprobe_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
kprobe_opcode_t *kprobe_addr(struct kprobe *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8113eec0)
Location: kernel/kprobes.c:1359
Inline: False
```
**Symbols:**

```
ffffffff8113eec0-ffffffff8113ef12: kprobe_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
kprobe_opcode_t *kprobe_addr(struct kprobe *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81141cc0)
Location: kernel/kprobes.c:1421
Inline: False
Direct callers:
  - kernel/kprobes.c:register_kretprobe
```
**Symbols:**

```
ffffffff81141cc0-ffffffff81141d1e: kprobe_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
kprobe_opcode_t *kprobe_addr(struct kprobe *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8114ea70)
Location: kernel/kprobes.c:1423
Inline: False
Direct callers:
  - kernel/kprobes.c:register_kretprobe
```
**Symbols:**

```
ffffffff8114ea70-ffffffff8114eace: kprobe_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
kprobe_opcode_t *kprobe_addr(struct kprobe *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8115d4f0)
Location: kernel/kprobes.c:1452
Inline: False
Direct callers:
  - kernel/kprobes.c:register_kretprobe
```
**Symbols:**

```
ffffffff8115d4f0-ffffffff8115d54e: kprobe_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
kprobe_opcode_t *kprobe_addr(struct kprobe *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8116a120)
Location: kernel/kprobes.c:1443
Inline: False
Direct callers:
  - kernel/kprobes.c:register_kretprobe
```
**Symbols:**

```
ffffffff8116a120-ffffffff8116a17e: kprobe_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
kprobe_opcode_t *kprobe_addr(struct kprobe *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81176e80)
Location: kernel/kprobes.c:1447
Inline: False
Direct callers:
  - kernel/kprobes.c:register_kretprobe
```
**Symbols:**

```
ffffffff81176e80-ffffffff81176edb: kprobe_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
kprobe_opcode_t *kprobe_addr(struct kprobe *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81182db0)
Location: kernel/kprobes.c:1492
Inline: False
Direct callers:
  - kernel/kprobes.c:register_kretprobe
```
**Symbols:**

```
ffffffff81182db0-ffffffff81182e0b: kprobe_addr (STB_LOCAL)
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
In kernel/kprobes.c (ffffffff81197b5c)
Location: kernel/kprobes.c:1532
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kretprobe
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
In kernel/kprobes.c (ffffffff81194965)
Location: kernel/kprobes.c:1496
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
In kernel/kprobes.c (ffffffff81195965)
Location: kernel/kprobes.c:1497
Inline: True
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
In kernel/kprobes.c (ffffffff811be8c5)
Location: kernel/kprobes.c:1489
Inline: True
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
In kernel/kprobes.c (ffffffff811f1b2b)
Location: kernel/kprobes.c:1490
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kprobe
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
In kernel/kprobes.c (ffffffff81238c47)
Location: kernel/kprobes.c:1487
Inline: True
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
In kernel/kprobes.c (ffffffff8124fda7)
Location: kernel/kprobes.c:1487
Inline: True
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
In kernel/kprobes.c (ffffffff81269cd2)
Location: kernel/kprobes.c:1487
Inline: True
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
In kernel/kprobes.c (ffff8000101f8bfc)
Location: kernel/kprobes.c:1492
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
In kernel/kprobes.c (c04393d8)
Location: kernel/kprobes.c:1492
Inline: True
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
In kernel/kprobes.c (c000000000270730)
Location: kernel/kprobes.c:1492
Inline: True
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
<summary>In <code>aws</code>: ✅</summary>

```c
kprobe_opcode_t *kprobe_addr(struct kprobe *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8117b3d0)
Location: kernel/kprobes.c:1492
Inline: False
Direct callers:
  - kernel/kprobes.c:register_kretprobe
```
**Symbols:**

```
ffffffff8117b3d0-ffffffff8117b42b: kprobe_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
kprobe_opcode_t *kprobe_addr(struct kprobe *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8116e570)
Location: kernel/kprobes.c:1492
Inline: False
Direct callers:
  - kernel/kprobes.c:register_kretprobe
```
**Symbols:**

```
ffffffff8116e570-ffffffff8116e5cb: kprobe_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
kprobe_opcode_t *kprobe_addr(struct kprobe *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff811791a0)
Location: kernel/kprobes.c:1492
Inline: False
Direct callers:
  - kernel/kprobes.c:register_kretprobe
```
**Symbols:**

```
ffffffff811791a0-ffffffff811791fb: kprobe_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
kprobe_opcode_t *kprobe_addr(struct kprobe *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81186a70)
Location: kernel/kprobes.c:1492
Inline: False
Direct callers:
  - kernel/kprobes.c:register_kretprobe
```
**Symbols:**

```
ffffffff81186a70-ffffffff81186acb: kprobe_addr (STB_LOCAL)
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
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
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
