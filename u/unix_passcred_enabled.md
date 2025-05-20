# Function: <code>unix_passcred_enabled</code>

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
In net/unix/af_unix.c (ffffffff817be322)
Location: net/unix/af_unix.c:1584
Inline: True
Inline callers:
  - net/unix/af_unix.c:maybe_init_creds
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
In net/unix/af_unix.c (ffffffff8182c17d)
Location: net/unix/af_unix.c:1569
Inline: True
Inline callers:
  - net/unix/af_unix.c:maybe_init_creds
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
In net/unix/af_unix.c (ffffffff8185dc2d)
Location: net/unix/af_unix.c:1574
Inline: True
Inline callers:
  - net/unix/af_unix.c:maybe_init_creds
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
In net/unix/af_unix.c (ffffffff818823d7)
Location: net/unix/af_unix.c:1581
Inline: True
Inline callers:
  - net/unix/af_unix.c:maybe_init_creds
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
In net/unix/af_unix.c (ffffffff81903547)
Location: net/unix/af_unix.c:1569
Inline: True
Inline callers:
  - net/unix/af_unix.c:maybe_init_creds
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
In net/unix/af_unix.c (ffffffff81959287)
Location: net/unix/af_unix.c:1559
Inline: True
Inline callers:
  - net/unix/af_unix.c:maybe_init_creds
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
In net/unix/af_unix.c (ffffffff8198de37)
Location: net/unix/af_unix.c:1576
Inline: True
Inline callers:
  - net/unix/af_unix.c:maybe_init_creds
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
In net/unix/af_unix.c (ffffffff819f9c9b)
Location: net/unix/af_unix.c:1512
Inline: True
Inline callers:
  - net/unix/af_unix.c:maybe_init_creds
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
In net/unix/af_unix.c (ffffffff81a3091b)
Location: net/unix/af_unix.c:1524
Inline: True
Inline callers:
  - net/unix/af_unix.c:maybe_init_creds
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
In net/unix/af_unix.c (ffffffff81b254d6)
Location: net/unix/af_unix.c:1548
Inline: True
Inline callers:
  - net/unix/af_unix.c:maybe_init_creds
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
In net/unix/af_unix.c (ffffffff81b3376c)
Location: net/unix/af_unix.c:1539
Inline: True
Inline callers:
  - net/unix/af_unix.c:maybe_init_creds
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
In net/unix/af_unix.c (ffffffff81b20c7c)
Location: net/unix/af_unix.c:1588
Inline: True
Inline callers:
  - net/unix/af_unix.c:maybe_init_creds
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
In net/unix/af_unix.c (ffffffff81be5d3c)
Location: net/unix/af_unix.c:1680
Inline: True
Inline callers:
  - net/unix/af_unix.c:maybe_init_creds
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
In net/unix/af_unix.c (ffffffff81d7f34b)
Location: net/unix/af_unix.c:1767
Inline: True
Inline callers:
  - net/unix/af_unix.c:maybe_init_creds
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool unix_passcred_enabled(const struct socket *sock, const struct sock *other);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81f490b0)
Location: net/unix/af_unix.c:1817
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
```
**Symbols:**

```
ffffffff81f490b0-ffffffff81f490ee: unix_passcred_enabled (STB_LOCAL)
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
In net/unix/af_unix.c (ffffffff81fad6f7)
Location: net/unix/af_unix.c:1842
Inline: True
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
In net/unix/af_unix.c (ffffffff82079fc7)
Location: net/unix/af_unix.c:1841
Inline: True
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
In net/unix/af_unix.c (ffff800010cef518)
Location: net/unix/af_unix.c:1524
Inline: True
Inline callers:
  - net/unix/af_unix.c:maybe_init_creds
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
In net/unix/af_unix.c (c0df8df8)
Location: net/unix/af_unix.c:1524
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
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
In net/unix/af_unix.c (c000000000e15380)
Location: net/unix/af_unix.c:1524
Inline: True
Inline callers:
  - net/unix/af_unix.c:maybe_init_creds
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
In net/unix/af_unix.c (ffffffe00083c52e)
Location: net/unix/af_unix.c:1524
Inline: True
Inline callers:
  - net/unix/af_unix.c:maybe_init_creds
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
In net/unix/af_unix.c (ffffffff819cffab)
Location: net/unix/af_unix.c:1524
Inline: True
Inline callers:
  - net/unix/af_unix.c:maybe_init_creds
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
In net/unix/af_unix.c (ffffffff8198cd6b)
Location: net/unix/af_unix.c:1524
Inline: True
Inline callers:
  - net/unix/af_unix.c:maybe_init_creds
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
In net/unix/af_unix.c (ffffffff81a3aa2b)
Location: net/unix/af_unix.c:1524
Inline: True
Inline callers:
  - net/unix/af_unix.c:maybe_init_creds
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
In net/unix/af_unix.c (ffffffff81a46f7b)
Location: net/unix/af_unix.c:1524
Inline: True
Inline callers:
  - net/unix/af_unix.c:maybe_init_creds
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
