# Function: <code>copy_peercred</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff817c1743)
Location: net/unix/af_unix.c:593
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff8182e735)
Location: net/unix/af_unix.c:593
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff818601bc)
Location: net/unix/af_unix.c:593
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff818848de)
Location: net/unix/af_unix.c:594
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81905ac4)
Location: net/unix/af_unix.c:594
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
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
In net/unix/af_unix.c (ffffffff8195d177)
Location: net/unix/af_unix.c:594
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
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
In net/unix/af_unix.c (ffffffff81991552)
Location: net/unix/af_unix.c:601
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
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
In net/unix/af_unix.c (ffffffff819fd420)
Location: net/unix/af_unix.c:598
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
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
In net/unix/af_unix.c (ffffffff81a340b0)
Location: net/unix/af_unix.c:598
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void copy_peercred(struct sock *sk, struct sock *peersk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81b243f0)
Location: net/unix/af_unix.c:602
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_connect
```
**Symbols:**

```
ffffffff81b243f0-ffffffff81b24498: copy_peercred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void copy_peercred(struct sock *sk, struct sock *peersk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81b32c10)
Location: net/unix/af_unix.c:602
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_connect
```
**Symbols:**

```
ffffffff81b32c10-ffffffff81b32cb8: copy_peercred (STB_LOCAL)
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
In net/unix/af_unix.c (ffffffff81b2533a)
Location: net/unix/af_unix.c:603
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
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
In net/unix/af_unix.c (ffffffff81bea38d)
Location: net/unix/af_unix.c:625
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
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
In net/unix/af_unix.c (ffffffff81d81d3f)
Location: net/unix/af_unix.c:667
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
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
In net/unix/af_unix.c (ffffffff81f4f27f)
Location: net/unix/af_unix.c:690
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
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
In net/unix/af_unix.c (ffffffff81faeb41)
Location: net/unix/af_unix.c:703
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
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
In net/unix/af_unix.c (ffffffff8207c058)
Location: net/unix/af_unix.c:702
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
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
In net/unix/af_unix.c (ffff800010cf403c)
Location: net/unix/af_unix.c:598
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
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
In net/unix/af_unix.c (c0dfb31c)
Location: net/unix/af_unix.c:598
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
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
In net/unix/af_unix.c (c000000000e1a4cc)
Location: net/unix/af_unix.c:598
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
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
In net/unix/af_unix.c (ffffffe00083fccc)
Location: net/unix/af_unix.c:598
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
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
In net/unix/af_unix.c (ffffffff819d3740)
Location: net/unix/af_unix.c:598
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
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
In net/unix/af_unix.c (ffffffff81990500)
Location: net/unix/af_unix.c:598
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
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
In net/unix/af_unix.c (ffffffff81a3e1c0)
Location: net/unix/af_unix.c:598
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
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
In net/unix/af_unix.c (ffffffff81a49c6f)
Location: net/unix/af_unix.c:598
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_connect
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
</ul>
