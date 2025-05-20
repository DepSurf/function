# Function: <code>convert___skb_to_skb</code>

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
In net/bpf/test_run.c (ffffffff8196d737)
Location: net/bpf/test_run.c:199
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
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
In net/bpf/test_run.c (ffffffff819a41a2)
Location: net/bpf/test_run.c:199
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int convert___skb_to_skb(struct sk_buff *skb, struct __sk_buff *__skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff81a7e440)
Location: net/bpf/test_run.c:310
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff81a7e440-ffffffff81a7e5a6: convert___skb_to_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int convert___skb_to_skb(struct sk_buff *skb, struct __sk_buff *__skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff81a87ad0)
Location: net/bpf/test_run.c:393
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff81a87ad0-ffffffff81a87c52: convert___skb_to_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int convert___skb_to_skb(struct sk_buff *skb, struct __sk_buff *__skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff81a709d0)
Location: net/bpf/test_run.c:467
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff81a709d0-ffffffff81a70b50: convert___skb_to_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int convert___skb_to_skb(struct sk_buff *skb, struct __sk_buff *__skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff81b2a220)
Location: net/bpf/test_run.c:468
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff81b2a220-ffffffff81b2a3a0: convert___skb_to_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int convert___skb_to_skb(struct sk_buff *skb, struct __sk_buff *__skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff81cb3e90)
Location: net/bpf/test_run.c:954
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff81cb3e90-ffffffff81cb4069: convert___skb_to_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int convert___skb_to_skb(struct sk_buff *skb, struct __sk_buff *__skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff81e720e0)
Location: net/bpf/test_run.c:986
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff81e720e0-ffffffff81e722b7: convert___skb_to_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int convert___skb_to_skb(struct sk_buff *skb, struct __sk_buff *__skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff81ece250)
Location: net/bpf/test_run.c:827
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff81ece250-ffffffff81ece427: convert___skb_to_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int convert___skb_to_skb(struct sk_buff *skb, struct __sk_buff *__skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff81f91a80)
Location: net/bpf/test_run.c:855
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff81f91a80-ffffffff81f91c57: convert___skb_to_skb (STB_LOCAL)
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
In net/bpf/test_run.c (ffff800010c535b4)
Location: net/bpf/test_run.c:199
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
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
In net/bpf/test_run.c (c0d62ef0)
Location: net/bpf/test_run.c:199
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
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
In net/bpf/test_run.c (c000000000d52c80)
Location: net/bpf/test_run.c:199
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
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
In net/bpf/test_run.c (ffffffe0007bdea2)
Location: net/bpf/test_run.c:199
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
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
In net/bpf/test_run.c (ffffffff81944012)
Location: net/bpf/test_run.c:199
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
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
In net/bpf/test_run.c (ffffffff818fdb02)
Location: net/bpf/test_run.c:199
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
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
In net/bpf/test_run.c (ffffffff819951a2)
Location: net/bpf/test_run.c:199
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
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
In net/bpf/test_run.c (ffffffff819b7d22)
Location: net/bpf/test_run.c:199
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
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
