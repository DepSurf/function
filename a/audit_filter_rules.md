# Function: <code>audit_filter_rules</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int audit_filter_rules(struct task_struct *tsk, struct audit_krule *rule, struct audit_context *ctx, struct audit_names *name, enum audit_state *state, bool task_creation);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81126cd0)
Location: kernel/auditsc.c:438
Inline: False
Direct callers:
  - kernel/auditsc.c:audit_filter_syscall
  - kernel/auditsc.c:audit_filter_inodes
  - kernel/auditsc.c:audit_alloc
```
**Symbols:**

```
ffffffff81126cd0-ffffffff81127afd: audit_filter_rules (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (ffffffff8112ede0)
Location: kernel/auditsc.c:439
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_alloc
  - kernel/auditsc.c:audit_filter_inodes
  - kernel/auditsc.c:audit_filter_syscall
```
**Symbols:**

```
ffffffff8112ede0-ffffffff8112fcd1: audit_filter_rules.constprop.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (ffffffff81138b20)
Location: kernel/auditsc.c:439
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_alloc
  - kernel/auditsc.c:audit_filter_inodes
  - kernel/auditsc.c:audit_filter_syscall
```
**Symbols:**

```
ffffffff81138b20-ffffffff81139a48: audit_filter_rules.constprop.11 (STB_LOCAL)
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
In kernel/auditsc.c (ffffffff8113a150)
Location: kernel/auditsc.c:440
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_alloc
```
**Symbols:**

```
ffffffff8113a150-ffffffff8113b073: audit_filter_rules.constprop.13 (STB_LOCAL)
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
In kernel/auditsc.c (ffffffff81146e20)
Location: kernel/auditsc.c:440
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_alloc
```
**Symbols:**

```
ffffffff81146e20-ffffffff81147d5e: audit_filter_rules.constprop.13 (STB_LOCAL)
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
In kernel/auditsc.c (ffffffff811557d0)
Location: kernel/auditsc.c:444
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_alloc
```
**Symbols:**

```
ffffffff811557d0-ffffffff81156744: audit_filter_rules.constprop.16 (STB_LOCAL)
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
In kernel/auditsc.c (ffffffff81162b80)
Location: kernel/auditsc.c:438
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_alloc
```
**Symbols:**

```
ffffffff81162b80-ffffffff81163c98: audit_filter_rules.constprop.18 (STB_LOCAL)
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
In kernel/auditsc.c (ffffffff8116fa80)
Location: kernel/auditsc.c:438
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_alloc
```
**Symbols:**

```
ffffffff8116fa80-ffffffff811708c9: audit_filter_rules.constprop.0 (STB_LOCAL)
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
In kernel/auditsc.c (ffffffff8117b900)
Location: kernel/auditsc.c:438
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_alloc
```
**Symbols:**

```
ffffffff8117b900-ffffffff8117c749: audit_filter_rules.constprop.0 (STB_LOCAL)
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
In kernel/auditsc.c (ffffffff8118de70)
Location: kernel/auditsc.c:449
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_alloc
```
**Symbols:**

```
ffffffff8118de70-ffffffff8118ebf3: audit_filter_rules.constprop.0 (STB_LOCAL)
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
In kernel/auditsc.c (ffffffff8118b020)
Location: kernel/auditsc.c:465
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_alloc
```
**Symbols:**

```
ffffffff8118b020-ffffffff8118bde6: audit_filter_rules.constprop.0 (STB_LOCAL)
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
In kernel/auditsc.c (ffffffff8118bec0)
Location: kernel/auditsc.c:465
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_alloc
```
**Symbols:**

```
ffffffff8118bec0-ffffffff8118cc9d: audit_filter_rules.constprop.0 (STB_LOCAL)
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
In kernel/auditsc.c (0)
Location: kernel/auditsc.c:471
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_alloc
```
**Symbols:**

```
ffffffff811b4b10-ffffffff811b58f8: audit_filter_rules.constprop.0 (STB_LOCAL)
ffffffff81cb3581-ffffffff81cb35ab: audit_filter_rules.constprop.0.cold (STB_LOCAL)
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
In kernel/auditsc.c (ffffffff811e75e0)
Location: kernel/auditsc.c:461
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_alloc
  - kernel/auditsc.c:audit_filter_syscall
  - kernel/auditsc.c:audit_filter_uring
```
**Symbols:**

```
ffffffff811e75e0-ffffffff811e83bd: audit_filter_rules.constprop.0 (STB_LOCAL)
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
In kernel/auditsc.c (ffffffff8122d740)
Location: kernel/auditsc.c:461
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_alloc
  - kernel/auditsc.c:__audit_filter_op
```
**Symbols:**

```
ffffffff8122d740-ffffffff8122e51d: audit_filter_rules.constprop.0 (STB_LOCAL)
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
In kernel/auditsc.c (ffffffff812435e0)
Location: kernel/auditsc.c:462
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_alloc
  - kernel/auditsc.c:__audit_filter_op
```
**Symbols:**

```
ffffffff812435e0-ffffffff81244520: audit_filter_rules.isra.0 (STB_LOCAL)
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
In kernel/auditsc.c (ffffffff8125d5b0)
Location: kernel/auditsc.c:464
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_alloc
  - kernel/auditsc.c:__audit_filter_op
```
**Symbols:**

```
ffffffff8125d5b0-ffffffff8125e410: audit_filter_rules.isra.0 (STB_LOCAL)
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
In kernel/auditsc.c (ffff8000101efce8)
Location: kernel/auditsc.c:438
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_alloc
```
**Symbols:**

```
ffff8000101efce8-ffff8000101f0860: audit_filter_rules.isra.0 (STB_LOCAL)
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
In kernel/auditsc.c (c0430b18)
Location: kernel/auditsc.c:438
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_alloc
```
**Symbols:**

```
c0430b18-c0431aa4: audit_filter_rules.constprop.0 (STB_LOCAL)
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
In kernel/auditsc.c (c000000000262b60)
Location: kernel/auditsc.c:438
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_alloc
```
**Symbols:**

```
c000000000262b60-c000000000263d14: audit_filter_rules.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (ffffffe000163978)
Location: kernel/auditsc.c:438
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_alloc
```
**Symbols:**

```
ffffffe000163978-ffffffe00016438e: audit_filter_rules.isra.0 (STB_LOCAL)
```
</details>
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
In kernel/auditsc.c (ffffffff81173f20)
Location: kernel/auditsc.c:438
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_alloc
```
**Symbols:**

```
ffffffff81173f20-ffffffff81174d69: audit_filter_rules.constprop.0 (STB_LOCAL)
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
In kernel/auditsc.c (ffffffff811670c0)
Location: kernel/auditsc.c:438
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_alloc
```
**Symbols:**

```
ffffffff811670c0-ffffffff81167f09: audit_filter_rules.constprop.0 (STB_LOCAL)
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
In kernel/auditsc.c (ffffffff81171cf0)
Location: kernel/auditsc.c:438
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_alloc
```
**Symbols:**

```
ffffffff81171cf0-ffffffff81172b39: audit_filter_rules.constprop.0 (STB_LOCAL)
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
In kernel/auditsc.c (ffffffff8117f500)
Location: kernel/auditsc.c:438
Inline: True
Direct callers:
  - kernel/auditsc.c:audit_alloc
```
**Symbols:**

```
ffffffff8117f500-ffffffff8118036f: audit_filter_rules.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
