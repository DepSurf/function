# Function: <code>register_kprobe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int register_kprobe(struct kprobe *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8112ecf0)
Location: kernel/kprobes.c:1481
Inline: True
Direct callers:
  - kernel/kprobes.c:register_kprobes
  - kernel/kprobes.c:register_jprobes
  - kernel/trace/trace_kprobe.c:__register_trace_kprobe
```
**Symbols:**

```
ffffffff8112ecf0-ffffffff8112f255: register_kprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int register_kprobe(struct kprobe *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81136f80)
Location: kernel/kprobes.c:1481
Inline: True
Direct callers:
  - kernel/kprobes.c:register_jprobes
  - kernel/kprobes.c:register_kprobes
  - kernel/trace/trace_kprobe.c:__register_trace_kprobe
```
**Symbols:**

```
ffffffff81136f80-ffffffff811374ee: register_kprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int register_kprobe(struct kprobe *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81140d00)
Location: kernel/kprobes.c:1481
Inline: True
Direct callers:
  - kernel/kprobes.c:register_jprobes
  - kernel/kprobes.c:register_kprobes
  - kernel/trace/trace_kprobe.c:__register_trace_kprobe
```
**Symbols:**

```
ffffffff81140d00-ffffffff8114126e: register_kprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int register_kprobe(struct kprobe *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81142470)
Location: kernel/kprobes.c:1526
Inline: True
Direct callers:
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:register_jprobe
```
**Symbols:**

```
ffffffff81142470-ffffffff81142a08: register_kprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int register_kprobe(struct kprobe *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8114f230)
Location: kernel/kprobes.c:1528
Inline: True
Direct callers:
  - kernel/kprobes.c:register_kretprobe
```
**Symbols:**

```
ffffffff8114f230-ffffffff8114f7c8: register_kprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int register_kprobe(struct kprobe *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8115dcd0)
Location: kernel/kprobes.c:1557
Inline: True
Direct callers:
  - kernel/kprobes.c:register_kretprobe
```
**Symbols:**

```
ffffffff8115dcd0-ffffffff8115e30e: register_kprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int register_kprobe(struct kprobe *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8116a8e0)
Location: kernel/kprobes.c:1548
Inline: True
Direct callers:
  - kernel/kprobes.c:register_kretprobe
```
**Symbols:**

```
ffffffff8116a8e0-ffffffff8116ae8f: register_kprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int register_kprobe(struct kprobe *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff811776c0)
Location: kernel/kprobes.c:1552
Inline: True
Direct callers:
  - kernel/kprobes.c:register_kretprobe
```
**Symbols:**

```
ffffffff811776c0-ffffffff81177bec: register_kprobe.part.0 (STB_LOCAL)
ffffffff81177bf0-ffffffff81177c7c: register_kprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int register_kprobe(struct kprobe *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff811835f0)
Location: kernel/kprobes.c:1598
Inline: True
Direct callers:
  - kernel/kprobes.c:register_kretprobe
```
**Symbols:**

```
ffffffff811835f0-ffffffff81183b2a: register_kprobe.part.0 (STB_LOCAL)
ffffffff81183b30-ffffffff81183b8d: register_kprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int register_kprobe(struct kprobe *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff811975f0)
Location: kernel/kprobes.c:1640
Inline: True
Direct callers:
  - kernel/kprobes.c:register_kretprobe
```
**Symbols:**

```
ffffffff811975f0-ffffffff81197847: register_kprobe.part.0 (STB_LOCAL)
ffffffff81197850-ffffffff81197946: register_kprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int register_kprobe(struct kprobe *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff81194700)
Location: kernel/kprobes.c:1604
Inline: True
```
**Symbols:**

```
ffffffff81194700-ffffffff81194957: register_kprobe.part.0 (STB_LOCAL)
ffffffff81194960-ffffffff81194a56: register_kprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int register_kprobe(struct kprobe *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff81195640)
Location: kernel/kprobes.c:1609
Inline: True
```
**Symbols:**

```
ffffffff81195640-ffffffff81195954: register_kprobe.part.0 (STB_LOCAL)
ffffffff81195960-ffffffff81195a58: register_kprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int register_kprobe(struct kprobe *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff811be8c0)
Location: kernel/kprobes.c:1601
Inline: True
```
**Symbols:**

```
ffffffff811be5a0-ffffffff811be8b6: register_kprobe.part.0 (STB_LOCAL)
ffffffff81cb3931-ffffffff81cb3945: register_kprobe.part.0.cold (STB_LOCAL)
ffffffff811be8c0-ffffffff811be9b8: register_kprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int register_kprobe(struct kprobe *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (0)
Location: kernel/kprobes.c:1603
Inline: False
```
**Symbols:**

```
ffffffff81e6473c-ffffffff81e64751: register_kprobe.cold (STB_LOCAL)
ffffffff811f1af0-ffffffff811f1dbf: register_kprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int register_kprobe(struct kprobe *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (0)
Location: kernel/kprobes.c:1601
Inline: False
```
**Symbols:**

```
ffffffff8205c7cb-ffffffff8205c7f5: register_kprobe.cold (STB_LOCAL)
ffffffff81238780-ffffffff81238a6a: register_kprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int register_kprobe(struct kprobe *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (0)
Location: kernel/kprobes.c:1613
Inline: False
```
**Symbols:**

```
ffffffff820db120-ffffffff820db14a: register_kprobe.cold (STB_LOCAL)
ffffffff8124f8e0-ffffffff8124fbca: register_kprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int register_kprobe(struct kprobe *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (0)
Location: kernel/kprobes.c:1613
Inline: False
```
**Symbols:**

```
ffffffff821b6e76-ffffffff821b6ea0: register_kprobe.cold (STB_LOCAL)
ffffffff81269810-ffffffff81269afa: register_kprobe (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int register_kprobe(struct kprobe *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffff8000101f8be0)
Location: kernel/kprobes.c:1598
Inline: True
```
**Symbols:**

```
ffff8000101f8be0-ffff8000101f9154: register_kprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int register_kprobe(struct kprobe *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (c0438e8c)
Location: kernel/kprobes.c:1598
Inline: True
```
**Symbols:**

```
c0438e8c-c04393c4: register_kprobe.part.0 (STB_LOCAL)
c04393c4-c0439478: register_kprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
int register_kprobe(struct kprobe *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (c000000000270010)
Location: kernel/kprobes.c:1598
Inline: True
Direct callers:
  - arch/powerpc/kernel/kprobes.c:arch_init_kprobes
```
**Symbols:**

```
c000000000270010-c000000000270708: register_kprobe.part.0 (STB_LOCAL)
c000000000270710-c0000000002707e4: register_kprobe (STB_GLOBAL)
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

```c
int register_kprobe(struct kprobe *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff8117bc10)
Location: kernel/kprobes.c:1598
Inline: True
Direct callers:
  - kernel/kprobes.c:register_kretprobe
```
**Symbols:**

```
ffffffff8117bc10-ffffffff8117c14a: register_kprobe.part.0 (STB_LOCAL)
ffffffff8117c150-ffffffff8117c1ad: register_kprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int register_kprobe(struct kprobe *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff8116edb0)
Location: kernel/kprobes.c:1598
Inline: True
Direct callers:
  - kernel/kprobes.c:register_kretprobe
```
**Symbols:**

```
ffffffff8116edb0-ffffffff8116f2ea: register_kprobe.part.0 (STB_LOCAL)
ffffffff8116f2f0-ffffffff8116f34d: register_kprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int register_kprobe(struct kprobe *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff811799e0)
Location: kernel/kprobes.c:1598
Inline: True
Direct callers:
  - kernel/kprobes.c:register_kretprobe
```
**Symbols:**

```
ffffffff811799e0-ffffffff81179f1a: register_kprobe.part.0 (STB_LOCAL)
ffffffff81179f20-ffffffff81179f7d: register_kprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int register_kprobe(struct kprobe *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff811872f0)
Location: kernel/kprobes.c:1598
Inline: True
Direct callers:
  - kernel/kprobes.c:register_kretprobe
```
**Symbols:**

```
ffffffff811872f0-ffffffff8118784e: register_kprobe.part.0 (STB_LOCAL)
ffffffff81187850-ffffffff811878ad: register_kprobe (STB_GLOBAL)
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
