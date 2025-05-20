# Function: <code>tcp_timeout_mark_lost</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81901644)
Location: net/ipv4/tcp_input.c:1941
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_enter_loss
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
In net/ipv4/tcp_input.c (ffffffff8192f724)
Location: net/ipv4/tcp_input.c:1932
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_enter_loss
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
In net/ipv4/tcp_input.c (ffffffff81992c94)
Location: net/ipv4/tcp_input.c:1952
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_enter_loss
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
In net/ipv4/tcp_input.c (ffffffff819c97e4)
Location: net/ipv4/tcp_input.c:1958
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tcp_timeout_mark_lost(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aaf9e0)
Location: net/ipv4/tcp_input.c:1960
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
**Symbols:**

```
ffffffff81aaf9e0-ffffffff81aafaf8: tcp_timeout_mark_lost (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcp_timeout_mark_lost(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ac08b0)
Location: net/ipv4/tcp_input.c:2063
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_enter_loss
```
**Symbols:**

```
ffffffff81ac08b0-ffffffff81ac09c8: tcp_timeout_mark_lost (STB_LOCAL)
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
In net/ipv4/tcp_input.c (ffffffff81aac974)
Location: net/ipv4/tcp_input.c:2063
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_enter_loss
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
In net/ipv4/tcp_input.c (ffffffff81b69464)
Location: net/ipv4/tcp_input.c:2097
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_enter_loss
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
In net/ipv4/tcp_input.c (ffffffff81cf8634)
Location: net/ipv4/tcp_input.c:2107
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_enter_loss
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
In net/ipv4/tcp_input.c (ffffffff81ebd104)
Location: net/ipv4/tcp_input.c:2106
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_enter_loss
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
In net/ipv4/tcp_input.c (ffffffff81f1b584)
Location: net/ipv4/tcp_input.c:2105
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_enter_loss
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
In net/ipv4/tcp_input.c (ffffffff81fdfd64)
Location: net/ipv4/tcp_input.c:2143
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_enter_loss
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
In net/ipv4/tcp_input.c (ffff800010c7c73c)
Location: net/ipv4/tcp_input.c:1958
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_enter_loss
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
In net/ipv4/tcp_input.c (c0d8b67c)
Location: net/ipv4/tcp_input.c:1958
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_enter_loss
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
In net/ipv4/tcp_input.c (c000000000d8632c)
Location: net/ipv4/tcp_input.c:1958
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_enter_loss
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
In net/ipv4/tcp_input.c (ffffffe0007defee)
Location: net/ipv4/tcp_input.c:1958
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_enter_loss
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
In net/ipv4/tcp_input.c (ffffffff81969654)
Location: net/ipv4/tcp_input.c:1958
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_enter_loss
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
In net/ipv4/tcp_input.c (ffffffff81923144)
Location: net/ipv4/tcp_input.c:1958
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_enter_loss
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
In net/ipv4/tcp_input.c (ffffffff819d3e24)
Location: net/ipv4/tcp_input.c:1958
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_enter_loss
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
In net/ipv4/tcp_input.c (ffffffff819dda04)
Location: net/ipv4/tcp_input.c:1958
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_enter_loss
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
