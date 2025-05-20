# Function: <code>bpf_lsm_xfrm_decode_session</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_lsm_xfrm_decode_session(struct sk_buff *skb, u32 *secid, int ckall);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81239510)
Location: include/linux/lsm_hook_defs.h:355
Inline: False
```
**Symbols:**

```
ffffffff81239510-ffffffff8123951d: bpf_lsm_xfrm_decode_session (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_lsm_xfrm_decode_session(struct sk_buff *skb, u32 *secid, int ckall);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8123dd00)
Location: include/linux/lsm_hook_defs.h:365
Inline: False
```
**Symbols:**

```
ffffffff8123dd00-ffffffff8123dd0d: bpf_lsm_xfrm_decode_session (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_lsm_xfrm_decode_session(struct sk_buff *skb, u32 *secid, int ckall);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff812787c0)
Location: include/linux/lsm_hook_defs.h:364
Inline: False
```
**Symbols:**

```
ffffffff812787c0-ffffffff812787cd: bpf_lsm_xfrm_decode_session (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_lsm_xfrm_decode_session(struct sk_buff *skb, u32 *secid, int ckall);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff812c90a0)
Location: include/linux/lsm_hook_defs.h:365
Inline: False
```
**Symbols:**

```
ffffffff812c90a0-ffffffff812c90b1: bpf_lsm_xfrm_decode_session (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_lsm_xfrm_decode_session(struct sk_buff *skb, u32 *secid, int ckall);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8132fb40)
Location: include/linux/lsm_hook_defs.h:373
Inline: False
```
**Symbols:**

```
ffffffff8132fb40-ffffffff8132fb51: bpf_lsm_xfrm_decode_session (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_lsm_xfrm_decode_session(struct sk_buff *skb, u32 *secid, int ckall);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff813607e0)
Location: include/linux/lsm_hook_defs.h:375
Inline: False
```
**Symbols:**

```
ffffffff813607e0-ffffffff813607f1: bpf_lsm_xfrm_decode_session (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_lsm_xfrm_decode_session(struct sk_buff *skb, u32 *secid, int ckall);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81389690)
Location: include/linux/lsm_hook_defs.h:385
Inline: False
```
**Symbols:**

```
ffffffff81389690-ffffffff813896a1: bpf_lsm_xfrm_decode_session (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
