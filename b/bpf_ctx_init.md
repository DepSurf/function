# Function: <code>bpf_ctx_init</code>

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
In net/bpf/test_run.c (ffffffff8196d5c0)
Location: net/bpf/test_run.c:128
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *bpf_ctx_init(const union bpf_attr *kattr, u32 max_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff819a3f20)
Location: net/bpf/test_run.c:128
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff819a3f20-ffffffff819a3ff0: bpf_ctx_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *bpf_ctx_init(const union bpf_attr *kattr, u32 max_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff81a7e5b0)
Location: net/bpf/test_run.c:239
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff81a7e5b0-ffffffff81a7e675: bpf_ctx_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *bpf_ctx_init(const union bpf_attr *kattr, u32 max_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff81a87d10)
Location: net/bpf/test_run.c:322
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff81a87d10-ffffffff81a87dd5: bpf_ctx_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *bpf_ctx_init(const union bpf_attr *kattr, u32 max_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff81a70900)
Location: net/bpf/test_run.c:396
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff81a70900-ffffffff81a709c2: bpf_ctx_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *bpf_ctx_init(const union bpf_attr *kattr, u32 max_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff81b2a3a0)
Location: net/bpf/test_run.c:397
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff81b2a3a0-ffffffff81b2a464: bpf_ctx_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *bpf_ctx_init(const union bpf_attr *kattr, u32 max_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff81cb36e0)
Location: net/bpf/test_run.c:883
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff81cb36e0-ffffffff81cb37a4: bpf_ctx_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *bpf_ctx_init(const union bpf_attr *kattr, u32 max_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff81e71920)
Location: net/bpf/test_run.c:915
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff81e71920-ffffffff81e719e4: bpf_ctx_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *bpf_ctx_init(const union bpf_attr *kattr, u32 max_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff81ecdc20)
Location: net/bpf/test_run.c:756
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_nf
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff81ecdc20-ffffffff81ecdce4: bpf_ctx_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *bpf_ctx_init(const union bpf_attr *kattr, u32 max_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff81f91450)
Location: net/bpf/test_run.c:784
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_nf
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff81f91450-ffffffff81f91514: bpf_ctx_init (STB_LOCAL)
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
void *bpf_ctx_init(const union bpf_attr *kattr, u32 max_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffff800010c52e20)
Location: net/bpf/test_run.c:128
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffff800010c52e20-ffff800010c52f2c: bpf_ctx_init (STB_LOCAL)
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
In net/bpf/test_run.c (c0d63480)
Location: net/bpf/test_run.c:128
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *bpf_ctx_init(const union bpf_attr *kattr, u32 max_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (c000000000d52920)
Location: net/bpf/test_run.c:128
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
c000000000d52920-c000000000d52ab8: bpf_ctx_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *bpf_ctx_init(const union bpf_attr *kattr, u32 max_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffe0007bdab4)
Location: net/bpf/test_run.c:128
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffe0007bdab4-ffffffe0007bdb82: bpf_ctx_init (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void *bpf_ctx_init(const union bpf_attr *kattr, u32 max_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff81943d90)
Location: net/bpf/test_run.c:128
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff81943d90-ffffffff81943e60: bpf_ctx_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *bpf_ctx_init(const union bpf_attr *kattr, u32 max_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff818fd880)
Location: net/bpf/test_run.c:128
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff818fd880-ffffffff818fd950: bpf_ctx_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *bpf_ctx_init(const union bpf_attr *kattr, u32 max_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff81994f20)
Location: net/bpf/test_run.c:128
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff81994f20-ffffffff81994ff0: bpf_ctx_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *bpf_ctx_init(const union bpf_attr *kattr, u32 max_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff819b7aa0)
Location: net/bpf/test_run.c:128
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff819b7aa0-ffffffff819b7b70: bpf_ctx_init (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
