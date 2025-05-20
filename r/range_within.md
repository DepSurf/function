# Function: <code>range_within</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811a463d)
Location: kernel/bpf/verifier.c:3456
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
In kernel/bpf/verifier.c (ffffffff811b7164)
Location: kernel/bpf/verifier.c:4285
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
In kernel/bpf/verifier.c (ffffffff811c64fe)
Location: kernel/bpf/verifier.c:5267
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
In kernel/bpf/verifier.c (ffffffff811d7d39)
Location: kernel/bpf/verifier.c:6669
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
In kernel/bpf/verifier.c (ffffffff811e4429)
Location: kernel/bpf/verifier.c:6684
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
In kernel/bpf/verifier.c (ffffffff81203979)
Location: kernel/bpf/verifier.c:7817
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool range_within(struct bpf_reg_state *old, struct bpf_reg_state *cur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81201eb0)
Location: kernel/bpf/verifier.c:8601
Inline: False
```
**Symbols:**

```
ffffffff81201eb0-ffffffff81201f06: range_within (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool range_within(struct bpf_reg_state *old, struct bpf_reg_state *cur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81202eb0)
Location: kernel/bpf/verifier.c:9779
Inline: False
```
**Symbols:**

```
ffffffff81202eb0-ffffffff81202f06: range_within (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool range_within(struct bpf_reg_state *old, struct bpf_reg_state *cur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81234fe0)
Location: kernel/bpf/verifier.c:10110
Inline: False
```
**Symbols:**

```
ffffffff81234fe0-ffffffff81235036: range_within (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool range_within(struct bpf_reg_state *old, struct bpf_reg_state *cur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81278950)
Location: kernel/bpf/verifier.c:11167
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:regsafe
```
**Symbols:**

```
ffffffff81278950-ffffffff812789b2: range_within (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool range_within(struct bpf_reg_state *old, struct bpf_reg_state *cur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812cef00)
Location: kernel/bpf/verifier.c:13139
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:regsafe
  - kernel/bpf/verifier.c:regsafe
```
**Symbols:**

```
ffffffff812cef00-ffffffff812cef62: range_within (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool range_within(struct bpf_reg_state *old, struct bpf_reg_state *cur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812f64c0)
Location: kernel/bpf/verifier.c:15118
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:regsafe
  - kernel/bpf/verifier.c:regsafe
  - kernel/bpf/verifier.c:regsafe
```
**Symbols:**

```
ffffffff812f64c0-ffffffff812f6522: range_within (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool range_within(struct bpf_reg_state *old, struct bpf_reg_state *cur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81314da0)
Location: kernel/bpf/verifier.c:16163
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:regsafe
  - kernel/bpf/verifier.c:regsafe
  - kernel/bpf/verifier.c:regsafe
```
**Symbols:**

```
ffffffff81314da0-ffffffff81314e02: range_within (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffff8000102678cc)
Location: kernel/bpf/verifier.c:6684
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
In kernel/bpf/verifier.c (c0499958)
Location: kernel/bpf/verifier.c:6684
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
In kernel/bpf/verifier.c (c00000000030d0e4)
Location: kernel/bpf/verifier.c:6684
Inline: True
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
In kernel/bpf/verifier.c (ffffffe0001a2d10)
Location: kernel/bpf/verifier.c:6684
Inline: True
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
In kernel/bpf/verifier.c (ffffffff811dca49)
Location: kernel/bpf/verifier.c:6684
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
In kernel/bpf/verifier.c (ffffffff811cf809)
Location: kernel/bpf/verifier.c:6684
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
In kernel/bpf/verifier.c (ffffffff811da819)
Location: kernel/bpf/verifier.c:6684
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
In kernel/bpf/verifier.c (ffffffff811e8c29)
Location: kernel/bpf/verifier.c:6684
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
