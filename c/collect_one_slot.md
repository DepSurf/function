# Function: <code>collect_one_slot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff8112d5c0)
Location: kernel/kprobes.c:204
Inline: True
Inline callers:
  - kernel/kprobes.c:collect_garbage_slots
  - kernel/kprobes.c:__free_insn_slot
Direct callers:
  - kernel/kprobes.c:collect_garbage_slots
  - kernel/kprobes.c:__free_insn_slot
```
**Symbols:**

```
ffffffff8112d5c0-ffffffff8112d61b: collect_one_slot.part.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int collect_one_slot(struct kprobe_insn_page *kip, int idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81135780)
Location: kernel/kprobes.c:204
Inline: True
Direct callers:
  - kernel/kprobes.c:__free_insn_slot
  - kernel/kprobes.c:collect_garbage_slots
```
**Symbols:**

```
ffffffff81135780-ffffffff811357fc: collect_one_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int collect_one_slot(struct kprobe_insn_page *kip, int idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8113f500)
Location: kernel/kprobes.c:204
Inline: True
Direct callers:
  - kernel/kprobes.c:__free_insn_slot
  - kernel/kprobes.c:collect_garbage_slots
```
**Symbols:**

```
ffffffff8113f500-ffffffff8113f57c: collect_one_slot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff81141f7f)
Location: kernel/kprobes.c:205
Inline: True
Inline callers:
  - kernel/kprobes.c:__free_insn_slot
  - kernel/kprobes.c:collect_garbage_slots
Direct callers:
  - kernel/kprobes.c:__free_insn_slot
  - kernel/kprobes.c:collect_garbage_slots
```
**Symbols:**

```
ffffffff81140a40-ffffffff81140a89: collect_one_slot.part.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff8114ed3f)
Location: kernel/kprobes.c:205
Inline: True
Inline callers:
  - kernel/kprobes.c:__free_insn_slot
  - kernel/kprobes.c:collect_garbage_slots
Direct callers:
  - kernel/kprobes.c:__free_insn_slot
  - kernel/kprobes.c:collect_garbage_slots
```
**Symbols:**

```
ffffffff8114d8e0-ffffffff8114d92f: collect_one_slot.part.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff8115d7bf)
Location: kernel/kprobes.c:205
Inline: True
Inline callers:
  - kernel/kprobes.c:__free_insn_slot
  - kernel/kprobes.c:collect_garbage_slots
Direct callers:
  - kernel/kprobes.c:__free_insn_slot
  - kernel/kprobes.c:collect_garbage_slots
```
**Symbols:**

```
ffffffff8115c2d0-ffffffff8115c332: collect_one_slot.part.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff8116a3df)
Location: kernel/kprobes.c:205
Inline: True
Inline callers:
  - kernel/kprobes.c:__free_insn_slot
  - kernel/kprobes.c:collect_garbage_slots
Direct callers:
  - kernel/kprobes.c:__free_insn_slot
  - kernel/kprobes.c:collect_garbage_slots
```
**Symbols:**

```
ffffffff811690c0-ffffffff81169122: collect_one_slot.part.20 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff8117713a)
Location: kernel/kprobes.c:192
Inline: True
Inline callers:
  - kernel/kprobes.c:__free_insn_slot
  - kernel/kprobes.c:collect_garbage_slots
Direct callers:
  - kernel/kprobes.c:__free_insn_slot
  - kernel/kprobes.c:collect_garbage_slots
```
**Symbols:**

```
ffffffff81175d50-ffffffff81175db1: collect_one_slot.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff81183065)
Location: kernel/kprobes.c:192
Inline: True
Inline callers:
  - kernel/kprobes.c:__free_insn_slot
  - kernel/kprobes.c:collect_garbage_slots
Direct callers:
  - kernel/kprobes.c:__free_insn_slot
  - kernel/kprobes.c:collect_garbage_slots
```
**Symbols:**

```
ffffffff81181bc0-ffffffff81181c21: collect_one_slot.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff81196ed6)
Location: kernel/kprobes.c:197
Inline: True
Inline callers:
  - kernel/kprobes.c:__free_insn_slot
  - kernel/kprobes.c:collect_garbage_slots
Direct callers:
  - kernel/kprobes.c:__free_insn_slot
  - kernel/kprobes.c:collect_garbage_slots
```
**Symbols:**

```
ffffffff811955e0-ffffffff81195643: collect_one_slot.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff81193fb2)
Location: kernel/kprobes.c:194
Inline: True
Inline callers:
  - kernel/kprobes.c:__free_insn_slot
  - kernel/kprobes.c:collect_garbage_slots
Direct callers:
  - kernel/kprobes.c:__free_insn_slot
  - kernel/kprobes.c:collect_garbage_slots
```
**Symbols:**

```
ffffffff81192280-ffffffff8119230b: collect_one_slot.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff81194fa2)
Location: kernel/kprobes.c:195
Inline: True
Inline callers:
  - kernel/kprobes.c:__free_insn_slot
  - kernel/kprobes.c:collect_garbage_slots
Direct callers:
  - kernel/kprobes.c:__free_insn_slot
  - kernel/kprobes.c:collect_garbage_slots
```
**Symbols:**

```
ffffffff81193150-ffffffff811931db: collect_one_slot.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff811bde62)
Location: kernel/kprobes.c:195
Inline: True
Inline callers:
  - kernel/kprobes.c:__free_insn_slot
  - kernel/kprobes.c:collect_garbage_slots
Direct callers:
  - kernel/kprobes.c:__free_insn_slot
  - kernel/kprobes.c:collect_garbage_slots
```
**Symbols:**

```
ffffffff811bc000-ffffffff811bc08b: collect_one_slot.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff811f11c5)
Location: kernel/kprobes.c:205
Inline: True
Inline callers:
  - kernel/kprobes.c:__free_insn_slot
  - kernel/kprobes.c:collect_garbage_slots
Direct callers:
  - kernel/kprobes.c:__free_insn_slot
  - kernel/kprobes.c:collect_garbage_slots
```
**Symbols:**

```
ffffffff811ef6a0-ffffffff811ef732: collect_one_slot.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff81237c95)
Location: kernel/kprobes.c:205
Inline: True
Inline callers:
  - kernel/kprobes.c:__free_insn_slot
  - kernel/kprobes.c:collect_garbage_slots
Direct callers:
  - kernel/kprobes.c:__free_insn_slot
  - kernel/kprobes.c:collect_garbage_slots
```
**Symbols:**

```
ffffffff81236080-ffffffff81236112: collect_one_slot.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff8124ed75)
Location: kernel/kprobes.c:205
Inline: True
Inline callers:
  - kernel/kprobes.c:__free_insn_slot
  - kernel/kprobes.c:collect_garbage_slots
Direct callers:
  - kernel/kprobes.c:__free_insn_slot
  - kernel/kprobes.c:collect_garbage_slots
```
**Symbols:**

```
ffffffff8124cea0-ffffffff8124cf32: collect_one_slot.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff81268ca5)
Location: kernel/kprobes.c:205
Inline: True
Inline callers:
  - kernel/kprobes.c:__free_insn_slot
  - kernel/kprobes.c:collect_garbage_slots
Direct callers:
  - kernel/kprobes.c:__free_insn_slot
  - kernel/kprobes.c:collect_garbage_slots
```
**Symbols:**

```
ffffffff81266da0-ffffffff81266e32: collect_one_slot.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffff8000101f899c)
Location: kernel/kprobes.c:192
Inline: True
Inline callers:
  - kernel/kprobes.c:__free_insn_slot
  - kernel/kprobes.c:collect_garbage_slots
Direct callers:
  - kernel/kprobes.c:__free_insn_slot
  - kernel/kprobes.c:collect_garbage_slots
```
**Symbols:**

```
ffff8000101f6f58-ffff8000101f6fc8: collect_one_slot.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (c04387a4)
Location: kernel/kprobes.c:192
Inline: True
Inline callers:
  - kernel/kprobes.c:__free_insn_slot
  - kernel/kprobes.c:collect_garbage_slots
Direct callers:
  - kernel/kprobes.c:__free_insn_slot
  - kernel/kprobes.c:collect_garbage_slots
```
**Symbols:**

```
c0437254-c04372bc: collect_one_slot.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (c00000000026f650)
Location: kernel/kprobes.c:192
Inline: True
Inline callers:
  - kernel/kprobes.c:__free_insn_slot
  - kernel/kprobes.c:collect_garbage_slots
Direct callers:
  - kernel/kprobes.c:__free_insn_slot
  - kernel/kprobes.c:collect_garbage_slots
```
**Symbols:**

```
c00000000026d490-c00000000026d538: collect_one_slot.part.0 (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff8117b685)
Location: kernel/kprobes.c:192
Inline: True
Inline callers:
  - kernel/kprobes.c:__free_insn_slot
  - kernel/kprobes.c:collect_garbage_slots
Direct callers:
  - kernel/kprobes.c:__free_insn_slot
  - kernel/kprobes.c:collect_garbage_slots
```
**Symbols:**

```
ffffffff8117a1e0-ffffffff8117a241: collect_one_slot.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff8116e825)
Location: kernel/kprobes.c:192
Inline: True
Inline callers:
  - kernel/kprobes.c:__free_insn_slot
  - kernel/kprobes.c:collect_garbage_slots
Direct callers:
  - kernel/kprobes.c:__free_insn_slot
  - kernel/kprobes.c:collect_garbage_slots
```
**Symbols:**

```
ffffffff8116d380-ffffffff8116d3e1: collect_one_slot.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff81179455)
Location: kernel/kprobes.c:192
Inline: True
Inline callers:
  - kernel/kprobes.c:__free_insn_slot
  - kernel/kprobes.c:collect_garbage_slots
Direct callers:
  - kernel/kprobes.c:__free_insn_slot
  - kernel/kprobes.c:collect_garbage_slots
```
**Symbols:**

```
ffffffff81177fb0-ffffffff81178011: collect_one_slot.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff81186d37)
Location: kernel/kprobes.c:192
Inline: True
Inline callers:
  - kernel/kprobes.c:__free_insn_slot
  - kernel/kprobes.c:collect_garbage_slots
Direct callers:
  - kernel/kprobes.c:__free_insn_slot
  - kernel/kprobes.c:collect_garbage_slots
```
**Symbols:**

```
ffffffff81185880-ffffffff811858e1: collect_one_slot.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
