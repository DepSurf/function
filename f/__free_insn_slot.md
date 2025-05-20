# Function: <code>__free_insn_slot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __free_insn_slot(struct kprobe_insn_cache *c, kprobe_opcode_t *slot, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8112e9e0)
Location: kernel/kprobes.c:247
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_remove_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_remove_optimized_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff8112e9e0-ffffffff8112eac9: __free_insn_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __free_insn_slot(struct kprobe_insn_cache *c, kprobe_opcode_t *slot, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81136c70)
Location: kernel/kprobes.c:247
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_remove_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_remove_optimized_kprobe
```
**Symbols:**

```
ffffffff81136c70-ffffffff81136d4e: __free_insn_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __free_insn_slot(struct kprobe_insn_cache *c, kprobe_opcode_t *slot, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff811409f0)
Location: kernel/kprobes.c:247
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_remove_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_remove_optimized_kprobe
```
**Symbols:**

```
ffffffff811409f0-ffffffff81140ace: __free_insn_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __free_insn_slot(struct kprobe_insn_cache *c, kprobe_opcode_t *slot, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81141ed0)
Location: kernel/kprobes.c:248
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_remove_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_remove_optimized_kprobe
```
**Symbols:**

```
ffffffff81141ed0-ffffffff81141fa9: __free_insn_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __free_insn_slot(struct kprobe_insn_cache *c, kprobe_opcode_t *slot, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8114ec90)
Location: kernel/kprobes.c:248
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_remove_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_remove_optimized_kprobe
```
**Symbols:**

```
ffffffff8114ec90-ffffffff8114ed69: __free_insn_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __free_insn_slot(struct kprobe_insn_cache *c, kprobe_opcode_t *slot, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8115d710)
Location: kernel/kprobes.c:248
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_remove_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_remove_optimized_kprobe
```
**Symbols:**

```
ffffffff8115d710-ffffffff8115d7d8: __free_insn_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __free_insn_slot(struct kprobe_insn_cache *c, kprobe_opcode_t *slot, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8116a330)
Location: kernel/kprobes.c:248
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_remove_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_remove_optimized_kprobe
```
**Symbols:**

```
ffffffff8116a330-ffffffff8116a3f8: __free_insn_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __free_insn_slot(struct kprobe_insn_cache *c, kprobe_opcode_t *slot, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (0)
Location: kernel/kprobes.c:235
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_remove_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_remove_optimized_kprobe
```
**Symbols:**

```
ffffffff811781da-ffffffff81178200: __free_insn_slot.cold (STB_LOCAL)
ffffffff81177080-ffffffff8117715f: __free_insn_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __free_insn_slot(struct kprobe_insn_cache *c, kprobe_opcode_t *slot, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81182fb0)
Location: kernel/kprobes.c:235
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_remove_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_remove_optimized_kprobe
```
**Symbols:**

```
ffffffff81182fb0-ffffffff8118308b: __free_insn_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __free_insn_slot(struct kprobe_insn_cache *c, kprobe_opcode_t *slot, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81196e20)
Location: kernel/kprobes.c:240
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_remove_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_remove_optimized_kprobe
```
**Symbols:**

```
ffffffff81196e20-ffffffff81196eef: __free_insn_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __free_insn_slot(struct kprobe_insn_cache *c, kprobe_opcode_t *slot, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81193ef0)
Location: kernel/kprobes.c:244
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_remove_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_remove_optimized_kprobe
```
**Symbols:**

```
ffffffff81193ef0-ffffffff81193fd1: __free_insn_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __free_insn_slot(struct kprobe_insn_cache *c, kprobe_opcode_t *slot, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81194ee0)
Location: kernel/kprobes.c:245
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_remove_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_remove_optimized_kprobe
```
**Symbols:**

```
ffffffff81194ee0-ffffffff81194fc1: __free_insn_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __free_insn_slot(struct kprobe_insn_cache *c, kprobe_opcode_t *slot, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff811bdda0)
Location: kernel/kprobes.c:245
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_remove_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_remove_optimized_kprobe
```
**Symbols:**

```
ffffffff811bdda0-ffffffff811bde81: __free_insn_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __free_insn_slot(struct kprobe_insn_cache *c, kprobe_opcode_t *slot, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff811f10f0)
Location: kernel/kprobes.c:256
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_remove_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_remove_optimized_kprobe
```
**Symbols:**

```
ffffffff811f10f0-ffffffff811f11e7: __free_insn_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __free_insn_slot(struct kprobe_insn_cache *c, kprobe_opcode_t *slot, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81237bc0)
Location: kernel/kprobes.c:256
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_remove_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_remove_optimized_kprobe
```
**Symbols:**

```
ffffffff81237bc0-ffffffff81237cb7: __free_insn_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __free_insn_slot(struct kprobe_insn_cache *c, kprobe_opcode_t *slot, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8124eca0)
Location: kernel/kprobes.c:256
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_remove_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_remove_optimized_kprobe
```
**Symbols:**

```
ffffffff8124eca0-ffffffff8124ed97: __free_insn_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __free_insn_slot(struct kprobe_insn_cache *c, kprobe_opcode_t *slot, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81268bd0)
Location: kernel/kprobes.c:256
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_remove_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_remove_optimized_kprobe
```
**Symbols:**

```
ffffffff81268bd0-ffffffff81268cc7: __free_insn_slot (STB_GLOBAL)
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
void __free_insn_slot(struct kprobe_insn_cache *c, kprobe_opcode_t *slot, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffff8000101f88a0)
Location: kernel/kprobes.c:235
Inline: False
Direct callers:
  - arch/arm64/kernel/probes/kprobes.c:arch_remove_kprobe
```
**Symbols:**

```
ffff8000101f88a0-ffff8000101f89dc: __free_insn_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __free_insn_slot(struct kprobe_insn_cache *c, kprobe_opcode_t *slot, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (c04386a4)
Location: kernel/kprobes.c:235
Inline: False
Direct callers:
  - arch/arm/probes/kprobes/core.c:arch_remove_kprobe
  - arch/arm/probes/kprobes/opt-arm.c:arch_remove_optimized_kprobe
  - arch/arm/probes/kprobes/opt-arm.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
c04386a4-c04387e4: __free_insn_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __free_insn_slot(struct kprobe_insn_cache *c, kprobe_opcode_t *slot, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (c00000000026f500)
Location: kernel/kprobes.c:235
Inline: False
Direct callers:
  - arch/powerpc/kernel/kprobes.c:arch_remove_kprobe
  - arch/powerpc/kernel/optprobes.c:arch_prepare_optimized_kprobe
  - arch/powerpc/kernel/optprobes.c:arch_remove_optimized_kprobe
```
**Symbols:**

```
c00000000026f500-c00000000026f69c: __free_insn_slot (STB_GLOBAL)
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
void __free_insn_slot(struct kprobe_insn_cache *c, kprobe_opcode_t *slot, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8117b5d0)
Location: kernel/kprobes.c:235
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_remove_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_remove_optimized_kprobe
```
**Symbols:**

```
ffffffff8117b5d0-ffffffff8117b6ab: __free_insn_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __free_insn_slot(struct kprobe_insn_cache *c, kprobe_opcode_t *slot, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8116e770)
Location: kernel/kprobes.c:235
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_remove_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_remove_optimized_kprobe
```
**Symbols:**

```
ffffffff8116e770-ffffffff8116e84b: __free_insn_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __free_insn_slot(struct kprobe_insn_cache *c, kprobe_opcode_t *slot, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff811793a0)
Location: kernel/kprobes.c:235
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_remove_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_remove_optimized_kprobe
```
**Symbols:**

```
ffffffff811793a0-ffffffff8117947b: __free_insn_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __free_insn_slot(struct kprobe_insn_cache *c, kprobe_opcode_t *slot, int dirty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81186c70)
Location: kernel/kprobes.c:235
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_remove_kprobe
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_remove_optimized_kprobe
```
**Symbols:**

```
ffffffff81186c70-ffffffff81186d56: __free_insn_slot (STB_GLOBAL)
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
