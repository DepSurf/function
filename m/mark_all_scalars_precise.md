# Function: <code>mark_all_scalars_precise</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d7680)
Location: kernel/bpf/verifier.c:1630
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
```
**Symbols:**

```
ffffffff811d7680-ffffffff811d770b: mark_all_scalars_precise.isra.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff811e3d70)
Location: kernel/bpf/verifier.c:1631
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
```
**Symbols:**

```
ffffffff811e3d70-ffffffff811e3dfb: mark_all_scalars_precise.isra.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff812030b0)
Location: kernel/bpf/verifier.c:1940
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
```
**Symbols:**

```
ffffffff812030b0-ffffffff81203139: mark_all_scalars_precise.constprop.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff81202f50)
Location: kernel/bpf/verifier.c:1992
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
```
**Symbols:**

```
ffffffff81202f50-ffffffff81202fd9: mark_all_scalars_precise.constprop.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff81203af0)
Location: kernel/bpf/verifier.c:2295
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
```
**Symbols:**

```
ffffffff81203af0-ffffffff81203b79: mark_all_scalars_precise.constprop.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff81235f80)
Location: kernel/bpf/verifier.c:2363
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
```
**Symbols:**

```
ffffffff81235f80-ffffffff8123606c: mark_all_scalars_precise.constprop.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff8127a230)
Location: kernel/bpf/verifier.c:2709
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
```
**Symbols:**

```
ffffffff8127a230-ffffffff8127a338: mark_all_scalars_precise.constprop.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff812d0a00)
Location: kernel/bpf/verifier.c:2976
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
```
**Symbols:**

```
ffffffff812d0a00-ffffffff812d0b08: mark_all_scalars_precise.constprop.0.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void mark_all_scalars_precise(struct bpf_verifier_env *env, struct bpf_verifier_state *st);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:3710
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
```
**Symbols:**

```
ffffffff812f8720-ffffffff812f88d0: mark_all_scalars_precise (STB_LOCAL)
ffffffff820de9cf-ffffffff820dea05: mark_all_scalars_precise.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void mark_all_scalars_precise(struct bpf_verifier_env *env, struct bpf_verifier_state *st);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:3872
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
```
**Symbols:**

```
ffffffff81317bb0-ffffffff81317d60: mark_all_scalars_precise (STB_LOCAL)
ffffffff821baa56-ffffffff821baa8c: mark_all_scalars_precise.cold (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffff800010266c00)
Location: kernel/bpf/verifier.c:1631
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
```
**Symbols:**

```
ffff800010266c00-ffff800010266cd0: mark_all_scalars_precise.isra.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (c049a4e4)
Location: kernel/bpf/verifier.c:1631
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
```
**Symbols:**

```
c049a4e4-c049a5a4: mark_all_scalars_precise.constprop.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (c00000000030c120)
Location: kernel/bpf/verifier.c:1631
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
```
**Symbols:**

```
c00000000030c120-c00000000030c1fc: mark_all_scalars_precise.isra.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffe0001a2182)
Location: kernel/bpf/verifier.c:1631
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
```
**Symbols:**

```
ffffffe0001a2182-ffffffe0001a221a: mark_all_scalars_precise.isra.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff811dc390)
Location: kernel/bpf/verifier.c:1631
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
```
**Symbols:**

```
ffffffff811dc390-ffffffff811dc41b: mark_all_scalars_precise.isra.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff811cf150)
Location: kernel/bpf/verifier.c:1631
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
```
**Symbols:**

```
ffffffff811cf150-ffffffff811cf1db: mark_all_scalars_precise.isra.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff811da160)
Location: kernel/bpf/verifier.c:1631
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
```
**Symbols:**

```
ffffffff811da160-ffffffff811da1eb: mark_all_scalars_precise.isra.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff811e8570)
Location: kernel/bpf/verifier.c:1631
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:__mark_chain_precision
```
**Symbols:**

```
ffffffff811e8570-ffffffff811e85fb: mark_all_scalars_precise.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
