# Function: <code>run_bpf_filter</code>

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
In net/core/sock_reuseport.c (ffffffff818e0b4d)
Location: net/core/sock_reuseport.c:223
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
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
In net/core/sock_reuseport.c (ffffffff8192f1ec)
Location: net/core/sock_reuseport.c:225
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
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
In net/core/sock_reuseport.c (ffffffff8196145c)
Location: net/core/sock_reuseport.c:225
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sock *run_bpf_filter(struct sock_reuseport *reuse, u16 socks, struct bpf_prog *prog, struct sk_buff *skb, int hdr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81a34ab0)
Location: net/core/sock_reuseport.c:217
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
**Symbols:**

```
ffffffff81a34ab0-ffffffff81a34bbd: run_bpf_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sock *run_bpf_filter(struct sock_reuseport *reuse, u16 socks, struct bpf_prog *prog, struct sk_buff *skb, int hdr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81a36df0)
Location: net/core/sock_reuseport.c:217
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
**Symbols:**

```
ffffffff81a36df0-ffffffff81a36f07: run_bpf_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sock *run_bpf_filter(struct sock_reuseport *reuse, u16 socks, struct bpf_prog *prog, struct sk_buff *skb, int hdr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81a1de70)
Location: net/core/sock_reuseport.c:217
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
**Symbols:**

```
ffffffff81a1de70-ffffffff81a1e063: run_bpf_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sock *run_bpf_filter(struct sock_reuseport *reuse, u16 socks, struct bpf_prog *prog, struct sk_buff *skb, int hdr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81ad1900)
Location: net/core/sock_reuseport.c:412
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
**Symbols:**

```
ffffffff81ad1900-ffffffff81ad1aef: run_bpf_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81c4f5c6)
Location: net/core/sock_reuseport.c:412
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81e04558)
Location: net/core/sock_reuseport.c:498
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81e76da8)
Location: net/core/sock_reuseport.c:498
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81f36d68)
Location: net/core/sock_reuseport.c:498
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
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
In net/core/sock_reuseport.c (ffff800010c04cd8)
Location: net/core/sock_reuseport.c:225
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
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
In net/core/sock_reuseport.c (c0d1e1a0)
Location: net/core/sock_reuseport.c:225
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
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
In net/core/sock_reuseport.c (c000000000ceee98)
Location: net/core/sock_reuseport.c:225
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
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
In net/core/sock_reuseport.c (ffffffe00078393c)
Location: net/core/sock_reuseport.c:225
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
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
In net/core/sock_reuseport.c (ffffffff8190142c)
Location: net/core/sock_reuseport.c:225
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
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
In net/core/sock_reuseport.c (ffffffff818bb25c)
Location: net/core/sock_reuseport.c:225
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
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
In net/core/sock_reuseport.c (ffffffff8195245c)
Location: net/core/sock_reuseport.c:225
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
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
In net/core/sock_reuseport.c (ffffffff81973ea7)
Location: net/core/sock_reuseport.c:225
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
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
</ul>
