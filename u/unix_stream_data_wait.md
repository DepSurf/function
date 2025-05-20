# Function: <code>unix_stream_data_wait</code>

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
In net/unix/af_unix.c (ffffffff817bf3b0)
Location: net/unix/af_unix.c:2209
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
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
In net/unix/af_unix.c (ffffffff8182c3fd)
Location: net/unix/af_unix.c:2201
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
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
In net/unix/af_unix.c (ffffffff8185deb4)
Location: net/unix/af_unix.c:2206
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
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
In net/unix/af_unix.c (ffffffff818833ed)
Location: net/unix/af_unix.c:2213
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
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
In net/unix/af_unix.c (ffffffff81903af4)
Location: net/unix/af_unix.c:2193
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
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
In net/unix/af_unix.c (ffffffff8195bfcb)
Location: net/unix/af_unix.c:2183
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
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
In net/unix/af_unix.c (ffffffff819907dd)
Location: net/unix/af_unix.c:2200
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
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
In net/unix/af_unix.c (ffffffff819fbec8)
Location: net/unix/af_unix.c:2136
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
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
In net/unix/af_unix.c (ffffffff81a32b58)
Location: net/unix/af_unix.c:2148
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int unix_stream_data_wait(struct sock *sk, long int timeo, struct sk_buff *last, unsigned int last_len, bool freezable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81b24720)
Location: net/unix/af_unix.c:2197
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffff81b24720-ffffffff81b2490f: unix_stream_data_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int unix_stream_data_wait(struct sock *sk, long int timeo, struct sk_buff *last, unsigned int last_len, bool freezable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81b33180)
Location: net/unix/af_unix.c:2188
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffff81b33180-ffffffff81b3338e: unix_stream_data_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int unix_stream_data_wait(struct sock *sk, long int timeo, struct sk_buff *last, unsigned int last_len, bool freezable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81b20ec0)
Location: net/unix/af_unix.c:2237
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffff81b20ec0-ffffffff81b210c9: unix_stream_data_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int unix_stream_data_wait(struct sock *sk, long int timeo, struct sk_buff *last, unsigned int last_len, bool freezable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81be5f80)
Location: net/unix/af_unix.c:2441
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffff81be5f80-ffffffff81be6189: unix_stream_data_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int unix_stream_data_wait(struct sock *sk, long int timeo, struct sk_buff *last, unsigned int last_len, bool freezable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81d7d170)
Location: net/unix/af_unix.c:2527
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffff81d7d170-ffffffff81d7d38d: unix_stream_data_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int unix_stream_data_wait(struct sock *sk, long int timeo, struct sk_buff *last, unsigned int last_len, bool freezable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81f4a4e0)
Location: net/unix/af_unix.c:2566
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffff81f4a4e0-ffffffff81f4a689: unix_stream_data_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int unix_stream_data_wait(struct sock *sk, long int timeo, struct sk_buff *last, unsigned int last_len, bool freezable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81faa180)
Location: net/unix/af_unix.c:2480
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffff81faa180-ffffffff81faa326: unix_stream_data_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int unix_stream_data_wait(struct sock *sk, long int timeo, struct sk_buff *last, unsigned int last_len, bool freezable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff820775a0)
Location: net/unix/af_unix.c:2491
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffff820775a0-ffffffff82077746: unix_stream_data_wait (STB_LOCAL)
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
In net/unix/af_unix.c (ffff800010cf22e8)
Location: net/unix/af_unix.c:2148
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
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
In net/unix/af_unix.c (c0dfa210)
Location: net/unix/af_unix.c:2148
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
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
In net/unix/af_unix.c (c000000000e18758)
Location: net/unix/af_unix.c:2148
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
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
In net/unix/af_unix.c (ffffffe00083f092)
Location: net/unix/af_unix.c:2148
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
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
In net/unix/af_unix.c (ffffffff819d21e8)
Location: net/unix/af_unix.c:2148
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
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
In net/unix/af_unix.c (ffffffff8198efa8)
Location: net/unix/af_unix.c:2148
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
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
In net/unix/af_unix.c (ffffffff81a3cc68)
Location: net/unix/af_unix.c:2148
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
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
In net/unix/af_unix.c (ffffffff81a4821a)
Location: net/unix/af_unix.c:2148
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
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
