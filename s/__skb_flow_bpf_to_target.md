# Function: <code>__skb_flow_bpf_to_target</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff818a9a05)
Location: net/core/flow_dissector.c:632
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
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
In net/core/flow_dissector.c (ffffffff818f52e3)
Location: net/core/flow_dissector.c:732
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
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
In net/core/flow_dissector.c (ffffffff819271b2)
Location: net/core/flow_dissector.c:757
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __skb_flow_bpf_to_target(const struct bpf_flow_keys *flow_keys, struct flow_dissector *flow_dissector, void *target_container);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff819fa7a0)
Location: net/core/flow_dissector.c:767
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
**Symbols:**

```
ffffffff819fa7a0-ffffffff819fa8b1: __skb_flow_bpf_to_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __skb_flow_bpf_to_target(const struct bpf_flow_keys *flow_keys, struct flow_dissector *flow_dissector, void *target_container);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff819fa3b0)
Location: net/core/flow_dissector.c:784
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
**Symbols:**

```
ffffffff819fa3b0-ffffffff819fa4c1: __skb_flow_bpf_to_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __skb_flow_bpf_to_target(const struct bpf_flow_keys *flow_keys, struct flow_dissector *flow_dissector, void *target_container);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff819e0590)
Location: net/core/flow_dissector.c:794
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
**Symbols:**

```
ffffffff819e0590-ffffffff819e06b2: __skb_flow_bpf_to_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __skb_flow_bpf_to_target(const struct bpf_flow_keys *flow_keys, struct flow_dissector *flow_dissector, void *target_container);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81a908e0)
Location: net/core/flow_dissector.c:795
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
**Symbols:**

```
ffffffff81a908e0-ffffffff81a90a02: __skb_flow_bpf_to_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __skb_flow_bpf_to_target(const struct bpf_flow_keys *flow_keys, struct flow_dissector *flow_dissector, void *target_container);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81c06930)
Location: net/core/flow_dissector.c:797
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
**Symbols:**

```
ffffffff81c06930-ffffffff81c06a69: __skb_flow_bpf_to_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __skb_flow_bpf_to_target(const struct bpf_flow_keys *flow_keys, struct flow_dissector *flow_dissector, void *target_container);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81db65a0)
Location: net/core/flow_dissector.c:821
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
**Symbols:**

```
ffffffff81db65a0-ffffffff81db66ea: __skb_flow_bpf_to_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __skb_flow_bpf_to_target(const struct bpf_flow_keys *flow_keys, struct flow_dissector *flow_dissector, void *target_container);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81e26950)
Location: net/core/flow_dissector.c:855
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
**Symbols:**

```
ffffffff81e26950-ffffffff81e26a9a: __skb_flow_bpf_to_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __skb_flow_bpf_to_target(const struct bpf_flow_keys *flow_keys, struct flow_dissector *flow_dissector, void *target_container);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81ee48e0)
Location: net/core/flow_dissector.c:899
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
**Symbols:**

```
ffffffff81ee48e0-ffffffff81ee4a2e: __skb_flow_bpf_to_target (STB_LOCAL)
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
In net/core/flow_dissector.c (ffff800010bc3734)
Location: net/core/flow_dissector.c:757
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
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
In net/core/flow_dissector.c (c0cdea74)
Location: net/core/flow_dissector.c:757
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
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
In net/core/flow_dissector.c (c000000000c9d890)
Location: net/core/flow_dissector.c:757
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
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
In net/core/flow_dissector.c (ffffffe0007501b6)
Location: net/core/flow_dissector.c:757
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
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
In net/core/flow_dissector.c (ffffffff818c71b2)
Location: net/core/flow_dissector.c:757
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
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
In net/core/flow_dissector.c (ffffffff818810f2)
Location: net/core/flow_dissector.c:757
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
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
In net/core/flow_dissector.c (ffffffff819181b2)
Location: net/core/flow_dissector.c:757
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
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
In net/core/flow_dissector.c (ffffffff81939408)
Location: net/core/flow_dissector.c:757
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
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
