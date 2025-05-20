# Function: <code>handle_incoming_queue</code>

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
In drivers/net/xen-netfront.c (ffffffff815fb913)
Location: drivers/net/xen-netfront.c:927
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
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
In drivers/net/xen-netfront.c (ffffffff8165bb79)
Location: drivers/net/xen-netfront.c:918
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
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
In drivers/net/xen-netfront.c (ffffffff81689957)
Location: drivers/net/xen-netfront.c:941
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
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
In drivers/net/xen-netfront.c (ffffffff8169f150)
Location: drivers/net/xen-netfront.c:942
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
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
In drivers/net/xen-netfront.c (ffffffff8170a2e7)
Location: drivers/net/xen-netfront.c:944
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
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
In drivers/net/xen-netfront.c (ffffffff81748984)
Location: drivers/net/xen-netfront.c:951
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
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
In drivers/net/xen-netfront.c (ffffffff8176ca2e)
Location: drivers/net/xen-netfront.c:950
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
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
In drivers/net/xen-netfront.c (ffffffff817aab80)
Location: drivers/net/xen-netfront.c:949
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
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
In drivers/net/xen-netfront.c (ffffffff817ce5c3)
Location: drivers/net/xen-netfront.c:951
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int handle_incoming_queue(struct netfront_queue *queue, struct sk_buff_head *rxq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff818996f0)
Location: drivers/net/xen-netfront.c:953
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
**Symbols:**

```
ffffffff818996f0-ffffffff818998bc: handle_incoming_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int handle_incoming_queue(struct netfront_queue *queue, struct sk_buff_head *rxq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff818a7c20)
Location: drivers/net/xen-netfront.c:1102
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
**Symbols:**

```
ffffffff818a7c20-ffffffff818a7dec: handle_incoming_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int handle_incoming_queue(struct netfront_queue *queue, struct sk_buff_head *rxq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff8188b4b0)
Location: drivers/net/xen-netfront.c:1100
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
**Symbols:**

```
ffffffff8188b4b0-ffffffff8188b62d: handle_incoming_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int handle_incoming_queue(struct netfront_queue *queue, struct sk_buff_head *rxq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff8191e3a0)
Location: drivers/net/xen-netfront.c:1181
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
**Symbols:**

```
ffffffff8191e3a0-ffffffff8191e51d: handle_incoming_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int handle_incoming_queue(struct netfront_queue *queue, struct sk_buff_head *rxq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81a72870)
Location: drivers/net/xen-netfront.c:1220
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
**Symbols:**

```
ffffffff81a72870-ffffffff81a729fb: handle_incoming_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int handle_incoming_queue(struct netfront_queue *queue, struct sk_buff_head *rxq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81c04fe0)
Location: drivers/net/xen-netfront.c:1220
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
**Symbols:**

```
ffffffff81c04fe0-ffffffff81c0516b: handle_incoming_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int handle_incoming_queue(struct netfront_queue *queue, struct sk_buff_head *rxq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81c6a6f0)
Location: drivers/net/xen-netfront.c:1220
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
**Symbols:**

```
ffffffff81c6a6f0-ffffffff81c6a87a: handle_incoming_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int handle_incoming_queue(struct netfront_queue *queue, struct sk_buff_head *rxq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81d1f0d0)
Location: drivers/net/xen-netfront.c:1221
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
**Symbols:**

```
ffffffff81d1f0d0-ffffffff81d1f25a: handle_incoming_queue (STB_LOCAL)
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
In drivers/net/xen-netfront.c (ffff800010a08a44)
Location: drivers/net/xen-netfront.c:951
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
</details>
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff817931e3)
Location: drivers/net/xen-netfront.c:983
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff817c3443)
Location: drivers/net/xen-netfront.c:951
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
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
In drivers/net/xen-netfront.c (ffffffff817dd703)
Location: drivers/net/xen-netfront.c:951
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
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
