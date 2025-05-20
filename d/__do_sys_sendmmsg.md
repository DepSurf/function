# Function: <code>__do_sys_sendmmsg</code>

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
In net/socket.c (ffffffff818739a5)
Location: net/socket.c:2249
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_sendmmsg
  - net/socket.c:__x64_sys_sendmmsg
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
In net/socket.c (ffffffff818942f5)
Location: net/socket.c:2236
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_sendmmsg
  - net/socket.c:__x64_sys_sendmmsg
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
In net/socket.c (ffffffff818de655)
Location: net/socket.c:2439
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_sendmmsg
  - net/socket.c:__x64_sys_sendmmsg
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
In net/socket.c (ffffffff81910775)
Location: net/socket.c:2480
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_sendmmsg
  - net/socket.c:__x64_sys_sendmmsg
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
In net/socket.c (ffffffff819e2b15)
Location: net/socket.c:2522
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_sendmmsg
  - net/socket.c:__x64_sys_sendmmsg
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
In net/socket.c (ffffffff819e2775)
Location: net/socket.c:2515
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_sendmmsg
  - net/socket.c:__x64_sys_sendmmsg
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
In net/socket.c (ffffffff819c87e5)
Location: net/socket.c:2505
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_sendmmsg
  - net/socket.c:__x64_sys_sendmmsg
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
In net/socket.c (ffffffff81a77b35)
Location: net/socket.c:2578
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_sendmmsg
  - net/socket.c:__x64_sys_sendmmsg
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
In net/socket.c (ffffffff81beafc5)
Location: net/socket.c:2654
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_sendmmsg
  - net/socket.c:__x64_sys_sendmmsg
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
In net/socket.c (ffffffff81d978e5)
Location: net/socket.c:2642
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_sendmmsg
  - net/socket.c:__x64_sys_sendmmsg
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
In net/socket.c (ffffffff81e05f55)
Location: net/socket.c:2680
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_sendmmsg
  - net/socket.c:__x64_sys_sendmmsg
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
In net/socket.c (ffffffff81ec2815)
Location: net/socket.c:2750
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_sendmmsg
  - net/socket.c:__x64_sys_sendmmsg
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
In net/socket.c (ffff800010ba89a8)
Location: net/socket.c:2480
Inline: True
Inline callers:
  - net/socket.c:__arm64_sys_sendmmsg
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
In net/socket.c (c0cc7324)
Location: net/socket.c:2480
Inline: True
Inline callers:
  - net/socket.c:__se_sys_sendmmsg
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
In net/socket.c (c000000000c7d18c)
Location: net/socket.c:2480
Inline: True
Inline callers:
  - net/socket.c:__se_sys_sendmmsg
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
In net/socket.c (ffffffe00073c048)
Location: net/socket.c:2480
Inline: True
Inline callers:
  - net/socket.c:__se_sys_sendmmsg
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
In net/socket.c (ffffffff818b0775)
Location: net/socket.c:2480
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_sendmmsg
  - net/socket.c:__x64_sys_sendmmsg
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
In net/socket.c (ffffffff8186a6c5)
Location: net/socket.c:2480
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_sendmmsg
  - net/socket.c:__x64_sys_sendmmsg
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
In net/socket.c (ffffffff81901775)
Location: net/socket.c:2480
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_sendmmsg
  - net/socket.c:__x64_sys_sendmmsg
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
In net/socket.c (ffffffff81922715)
Location: net/socket.c:2480
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_sendmmsg
  - net/socket.c:__x64_sys_sendmmsg
```
</details>
</li>
</ul>

## Differences
