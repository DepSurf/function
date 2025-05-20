# Function: <code>audit_fd_pair</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff81215db8)
Location: include/linux/audit.h:263
Inline: True
```
```
In net/socket.c (ffffffff816fef71)
Location: include/linux/audit.h:263
Inline: True
Inline callers:
  - net/socket.c:SyS_socketcall
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8123cc16)
Location: include/linux/audit.h:366
Inline: True
```
```
In net/socket.c (ffffffff81766947)
Location: include/linux/audit.h:366
Inline: True
Inline callers:
  - net/socket.c:SyS_socketcall
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8124f976)
Location: include/linux/audit.h:366
Inline: True
```
```
In net/socket.c (ffffffff817939c7)
Location: include/linux/audit.h:366
Inline: True
Inline callers:
  - net/socket.c:SyS_socketcall
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8125b8c4)
Location: include/linux/audit.h:365
Inline: True
```
```
In net/socket.c (ffffffff817b2049)
Location: include/linux/audit.h:365
Inline: True
Inline callers:
  - net/socket.c:SyS_socketcall
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8127dc94)
Location: include/linux/audit.h:358
Inline: True
```
```
In net/socket.c (ffffffff8182a0b1)
Location: include/linux/audit.h:358
Inline: True
Inline callers:
  - net/socket.c:SyS_socketcall
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812a4c34)
Location: include/linux/audit.h:362
Inline: True
```
```
In net/socket.c (ffffffff818726ea)
Location: include/linux/audit.h:362
Inline: True
Inline callers:
  - net/socket.c:__sys_socketpair
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812b9d04)
Location: include/linux/audit.h:361
Inline: True
```
```
In net/socket.c (ffffffff8189303a)
Location: include/linux/audit.h:361
Inline: True
Inline callers:
  - net/socket.c:__sys_socketpair
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812d6984)
Location: include/linux/audit.h:394
Inline: True
```
```
In net/socket.c (ffffffff818dd33c)
Location: include/linux/audit.h:394
Inline: True
Inline callers:
  - net/socket.c:__sys_socketpair
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812e84f4)
Location: include/linux/audit.h:387
Inline: True
```
```
In net/socket.c (ffffffff8190f39c)
Location: include/linux/audit.h:387
Inline: True
Inline callers:
  - net/socket.c:__sys_socketpair
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8131eb86)
Location: include/linux/audit.h:406
Inline: True
```
```
In net/socket.c (ffffffff819e0c9c)
Location: include/linux/audit.h:406
Inline: True
Inline callers:
  - net/socket.c:__sys_socketpair
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8132a0d6)
Location: include/linux/audit.h:423
Inline: True
```
```
In net/socket.c (ffffffff819e04f2)
Location: include/linux/audit.h:423
Inline: True
Inline callers:
  - net/socket.c:__sys_socketpair
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff81330086)
Location: include/linux/audit.h:423
Inline: True
```
```
In net/socket.c (ffffffff819c656d)
Location: include/linux/audit.h:423
Inline: True
Inline callers:
  - net/socket.c:__sys_socketpair
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8137d846)
Location: include/linux/audit.h:423
Inline: True
```
```
In net/socket.c (ffffffff81a7588d)
Location: include/linux/audit.h:423
Inline: True
Inline callers:
  - net/socket.c:__sys_socketpair
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff813fd865)
Location: include/linux/audit.h:450
Inline: True
```
```
In net/socket.c (ffffffff81be8810)
Location: include/linux/audit.h:450
Inline: True
Inline callers:
  - net/socket.c:__sys_socketpair
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff81487465)
Location: include/linux/audit.h:447
Inline: True
```
```
In net/socket.c (ffffffff81d94f20)
Location: include/linux/audit.h:447
Inline: True
Inline callers:
  - net/socket.c:__sys_socketpair
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff814bc265)
Location: include/linux/audit.h:446
Inline: True
```
```
In net/socket.c (ffffffff81e03551)
Location: include/linux/audit.h:446
Inline: True
Inline callers:
  - net/socket.c:__sys_socketpair
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff814ee795)
Location: include/linux/audit.h:445
Inline: True
```
```
In net/socket.c (ffffffff81ebff81)
Location: include/linux/audit.h:445
Inline: True
Inline callers:
  - net/socket.c:__sys_socketpair
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffff8000103913bc)
Location: include/linux/audit.h:387
Inline: True
```
```
In net/socket.c (ffff800010ba75d4)
Location: include/linux/audit.h:387
Inline: True
Inline callers:
  - net/socket.c:__sys_socketpair
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pipe.c (c0577de8)
Location: include/linux/audit.h:387
Inline: True
```
```
In net/socket.c (c0cc6060)
Location: include/linux/audit.h:387
Inline: True
Inline callers:
  - net/socket.c:__sys_socketpair
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pipe.c (c0000000004894d8)
Location: include/linux/audit.h:387
Inline: True
```
```
In net/socket.c (c000000000c7b9f4)
Location: include/linux/audit.h:387
Inline: True
Inline callers:
  - net/socket.c:__sys_socketpair
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffe000260a60)
Location: include/linux/audit.h:387
Inline: True
```
```
In net/socket.c (ffffffe00073afd2)
Location: include/linux/audit.h:387
Inline: True
Inline callers:
  - net/socket.c:__sys_socketpair
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812e0ad4)
Location: include/linux/audit.h:387
Inline: True
```
```
In net/socket.c (ffffffff818af39c)
Location: include/linux/audit.h:387
Inline: True
Inline callers:
  - net/socket.c:__sys_socketpair
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812d1714)
Location: include/linux/audit.h:387
Inline: True
```
```
In net/socket.c (ffffffff818692ec)
Location: include/linux/audit.h:387
Inline: True
Inline callers:
  - net/socket.c:__sys_socketpair
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812de8e4)
Location: include/linux/audit.h:387
Inline: True
```
```
In net/socket.c (ffffffff8190039c)
Location: include/linux/audit.h:387
Inline: True
Inline callers:
  - net/socket.c:__sys_socketpair
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812ef854)
Location: include/linux/audit.h:387
Inline: True
```
```
In net/socket.c (ffffffff8192138c)
Location: include/linux/audit.h:387
Inline: True
Inline callers:
  - net/socket.c:__sys_socketpair
```
</details>
</li>
</ul>

## Differences
