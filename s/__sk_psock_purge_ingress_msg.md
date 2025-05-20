# Function: <code>__sk_psock_purge_ingress_msg</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
void __sk_psock_purge_ingress_msg(struct sk_psock *psock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff818e7210)
Location: net/core/skmsg.c:516
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/ipv4/tcp_bpf.c:tcp_bpf_remove
```
**Symbols:**

```
ffffffff818e7210-ffffffff818e72c9: __sk_psock_purge_ingress_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __sk_psock_purge_ingress_msg(struct sk_psock *psock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81936ba0)
Location: net/core/skmsg.c:526
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
**Symbols:**

```
ffffffff81936ba0-ffffffff81936c5e: __sk_psock_purge_ingress_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __sk_psock_purge_ingress_msg(struct sk_psock *psock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81969a70)
Location: net/core/skmsg.c:535
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
**Symbols:**

```
ffffffff81969a70-ffffffff81969b2e: __sk_psock_purge_ingress_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __sk_psock_purge_ingress_msg(struct sk_psock *psock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81a3d540)
Location: net/core/skmsg.c:536
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
**Symbols:**

```
ffffffff81a3d540-ffffffff81a3d5fe: __sk_psock_purge_ingress_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __sk_psock_purge_ingress_msg(struct sk_psock *psock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81a40120)
Location: net/core/skmsg.c:621
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
**Symbols:**

```
ffffffff81a40120-ffffffff81a401de: __sk_psock_purge_ingress_msg (STB_GLOBAL)
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
In net/core/skmsg.c (ffffffff81a4ee2f)
Location: net/core/skmsg.c:747
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81b0799f)
Location: net/core/skmsg.c:742
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_stop
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
In net/core/skmsg.c (ffffffff81c8d739)
Location: net/core/skmsg.c:762
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_stop
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
In net/core/skmsg.c (ffffffff81e485d6)
Location: net/core/skmsg.c:769
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_stop
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
In net/core/skmsg.c (ffffffff81ea28c2)
Location: net/core/skmsg.c:764
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_destroy
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
In net/core/skmsg.c (ffffffff81f65962)
Location: net/core/skmsg.c:768
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_destroy
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
void __sk_psock_purge_ingress_msg(struct sk_psock *psock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffff800010c0fc70)
Location: net/core/skmsg.c:535
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
**Symbols:**

```
ffff800010c0fc70-ffff800010c0fd1c: __sk_psock_purge_ingress_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __sk_psock_purge_ingress_msg(struct sk_psock *psock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (c0d27a90)
Location: net/core/skmsg.c:535
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
**Symbols:**

```
c0d27a90-c0d27b14: __sk_psock_purge_ingress_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __sk_psock_purge_ingress_msg(struct sk_psock *psock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (c000000000cfbe40)
Location: net/core/skmsg.c:535
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
**Symbols:**

```
c000000000cfbe40-c000000000cfbf34: __sk_psock_purge_ingress_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __sk_psock_purge_ingress_msg(struct sk_psock *psock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffe00078c21a)
Location: net/core/skmsg.c:535
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
**Symbols:**

```
ffffffe00078c21a-ffffffe00078c2aa: __sk_psock_purge_ingress_msg (STB_GLOBAL)
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
void __sk_psock_purge_ingress_msg(struct sk_psock *psock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81909a40)
Location: net/core/skmsg.c:535
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
**Symbols:**

```
ffffffff81909a40-ffffffff81909afe: __sk_psock_purge_ingress_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __sk_psock_purge_ingress_msg(struct sk_psock *psock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff818c3850)
Location: net/core/skmsg.c:535
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
**Symbols:**

```
ffffffff818c3850-ffffffff818c390e: __sk_psock_purge_ingress_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __sk_psock_purge_ingress_msg(struct sk_psock *psock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff8195aa70)
Location: net/core/skmsg.c:535
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
**Symbols:**

```
ffffffff8195aa70-ffffffff8195ab2e: __sk_psock_purge_ingress_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __sk_psock_purge_ingress_msg(struct sk_psock *psock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff8197cc90)
Location: net/core/skmsg.c:535
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
**Symbols:**

```
ffffffff8197cc90-ffffffff8197cd4e: __sk_psock_purge_ingress_msg (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
