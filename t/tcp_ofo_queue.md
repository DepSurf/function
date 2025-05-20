# Function: <code>tcp_ofo_queue</code>

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
In net/ipv4/tcp_input.c (ffffffff8177012c)
Location: net/ipv4/tcp_input.c:4278
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
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
In net/ipv4/tcp_input.c (ffffffff817def7b)
Location: net/ipv4/tcp_input.c:4342
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
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
In net/ipv4/tcp_input.c (ffffffff8180f310)
Location: net/ipv4/tcp_input.c:4358
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
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
In net/ipv4/tcp_input.c (ffffffff8182f5de)
Location: net/ipv4/tcp_input.c:4317
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
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
In net/ipv4/tcp_input.c (ffffffff818aef49)
Location: net/ipv4/tcp_input.c:4294
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
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
In net/ipv4/tcp_input.c (ffffffff81904782)
Location: net/ipv4/tcp_input.c:4394
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
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
In net/ipv4/tcp_input.c (ffffffff81932944)
Location: net/ipv4/tcp_input.c:4411
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
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
In net/ipv4/tcp_input.c (ffffffff8199648a)
Location: net/ipv4/tcp_input.c:4428
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
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
In net/ipv4/tcp_input.c (ffffffff819cd004)
Location: net/ipv4/tcp_input.c:4478
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tcp_ofo_queue(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab8a70)
Location: net/ipv4/tcp_input.c:4507
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
```
**Symbols:**

```
ffffffff81ab8a70-ffffffff81ab8c52: tcp_ofo_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcp_ofo_queue(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ac3de0)
Location: net/ipv4/tcp_input.c:4645
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
```
**Symbols:**

```
ffffffff81ac3de0-ffffffff81ac3fc2: tcp_ofo_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tcp_ofo_queue(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81aaeef0)
Location: net/ipv4/tcp_input.c:4655
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
```
**Symbols:**

```
ffffffff81aaeef0-ffffffff81aaf0ce: tcp_ofo_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void tcp_ofo_queue(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:4689
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
```
**Symbols:**

```
ffffffff81b6bbd0-ffffffff81b6bdc6: tcp_ofo_queue (STB_LOCAL)
ffffffff81d3ac40-ffffffff81d3ac62: tcp_ofo_queue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void tcp_ofo_queue(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:4708
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
```
**Symbols:**

```
ffffffff81cfad80-ffffffff81cfaf73: tcp_ofo_queue (STB_LOCAL)
ffffffff81f074eb-ffffffff81f0750d: tcp_ofo_queue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void tcp_ofo_queue(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:4721
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
```
**Symbols:**

```
ffffffff81ebf890-ffffffff81ebfa83: tcp_ofo_queue (STB_LOCAL)
ffffffff820aef63-ffffffff820aef85: tcp_ofo_queue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void tcp_ofo_queue(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:4726
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
```
**Symbols:**

```
ffffffff81f1dd80-ffffffff81f1df73: tcp_ofo_queue (STB_LOCAL)
ffffffff82130359-ffffffff8213037b: tcp_ofo_queue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void tcp_ofo_queue(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_input.c (0)
Location: net/ipv4/tcp_input.c:4857
Inline: False
Direct callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
```
**Symbols:**

```
ffffffff81fe2450-ffffffff81fe2654: tcp_ofo_queue (STB_LOCAL)
ffffffff82211d82-ffffffff82211da4: tcp_ofo_queue.cold (STB_LOCAL)
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
In net/ipv4/tcp_input.c (ffff800010c7fb5c)
Location: net/ipv4/tcp_input.c:4478
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
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
In net/ipv4/tcp_input.c (c0d8ece4)
Location: net/ipv4/tcp_input.c:4478
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
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
In net/ipv4/tcp_input.c (c000000000d8a470)
Location: net/ipv4/tcp_input.c:4478
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
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
In net/ipv4/tcp_input.c (ffffffe0007e1c04)
Location: net/ipv4/tcp_input.c:4478
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
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
In net/ipv4/tcp_input.c (ffffffff8196ce74)
Location: net/ipv4/tcp_input.c:4478
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
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
In net/ipv4/tcp_input.c (ffffffff81926964)
Location: net/ipv4/tcp_input.c:4478
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
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
In net/ipv4/tcp_input.c (ffffffff819d7644)
Location: net/ipv4/tcp_input.c:4478
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
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
In net/ipv4/tcp_input.c (ffffffff819e1264)
Location: net/ipv4/tcp_input.c:4478
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue
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
