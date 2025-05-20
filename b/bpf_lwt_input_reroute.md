# Function: <code>bpf_lwt_input_reroute</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81942bd6)
Location: net/core/lwt_bpf.c:86
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
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
In net/core/lwt_bpf.c (ffffffff81977b2a)
Location: net/core/lwt_bpf.c:86
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
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
In net/core/lwt_bpf.c (ffffffff81a4d2ba)
Location: net/core/lwt_bpf.c:86
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
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
In net/core/lwt_bpf.c (ffffffff81a52f7a)
Location: net/core/lwt_bpf.c:86
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
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
In net/core/lwt_bpf.c (ffffffff81a3878a)
Location: net/core/lwt_bpf.c:86
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_lwt_input_reroute(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81aee590)
Location: net/core/lwt_bpf.c:86
Inline: False
Direct callers:
  - net/core/lwt_bpf.c:bpf_input
```
**Symbols:**

```
ffffffff81aee590-ffffffff81aee71c: bpf_lwt_input_reroute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_lwt_input_reroute(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81c71480)
Location: net/core/lwt_bpf.c:87
Inline: False
Direct callers:
  - net/core/lwt_bpf.c:bpf_input
```
**Symbols:**

```
ffffffff81c71480-ffffffff81c7165f: bpf_lwt_input_reroute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_lwt_input_reroute(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81e29540)
Location: net/core/lwt_bpf.c:87
Inline: False
Direct callers:
  - net/core/lwt_bpf.c:bpf_input
```
**Symbols:**

```
ffffffff81e29540-ffffffff81e2971f: bpf_lwt_input_reroute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_lwt_input_reroute(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81e9eb70)
Location: net/core/lwt_bpf.c:86
Inline: False
Direct callers:
  - net/core/lwt_bpf.c:bpf_input
```
**Symbols:**

```
ffffffff81e9eb70-ffffffff81e9ed4b: bpf_lwt_input_reroute (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_lwt_input_reroute(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81f612e0)
Location: net/core/lwt_bpf.c:86
Inline: False
Direct callers:
  - net/core/lwt_bpf.c:bpf_input
```
**Symbols:**

```
ffffffff81f612e0-ffffffff81f614bb: bpf_lwt_input_reroute (STB_LOCAL)
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
In net/core/lwt_bpf.c (ffff800010c1f104)
Location: net/core/lwt_bpf.c:86
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
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
In net/core/lwt_bpf.c (c0d36340)
Location: net/core/lwt_bpf.c:86
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
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
In net/core/lwt_bpf.c (c000000000d10094)
Location: net/core/lwt_bpf.c:86
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
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
In net/core/lwt_bpf.c (ffffffe000798060)
Location: net/core/lwt_bpf.c:86
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
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
In net/core/lwt_bpf.c (ffffffff8191799a)
Location: net/core/lwt_bpf.c:86
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
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
In net/core/lwt_bpf.c (ffffffff818d174a)
Location: net/core/lwt_bpf.c:86
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
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
In net/core/lwt_bpf.c (ffffffff81968b2a)
Location: net/core/lwt_bpf.c:86
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
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
In net/core/lwt_bpf.c (ffffffff8198af0a)
Location: net/core/lwt_bpf.c:86
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_input
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
