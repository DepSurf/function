# Function: <code>inet_wait_for_connect</code>

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
In net/ipv4/af_inet.c (ffffffff81793650)
Location: net/ipv4/af_inet.c:535
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
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
In net/ipv4/af_inet.c (ffffffff81800e54)
Location: net/ipv4/af_inet.c:539
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
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
In net/ipv4/af_inet.c (ffffffff81831d96)
Location: net/ipv4/af_inet.c:544
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
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
In net/ipv4/af_inet.c (ffffffff81853305)
Location: net/ipv4/af_inet.c:544
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
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
In net/ipv4/af_inet.c (ffffffff818d315b)
Location: net/ipv4/af_inet.c:545
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
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
In net/ipv4/af_inet.c (ffffffff8192954a)
Location: net/ipv4/af_inet.c:575
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
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
In net/ipv4/af_inet.c (ffffffff819586fa)
Location: net/ipv4/af_inet.c:575
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
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
In net/ipv4/af_inet.c (ffffffff819bd242)
Location: net/ipv4/af_inet.c:575
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
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
In net/ipv4/af_inet.c (ffffffff819f3e52)
Location: net/ipv4/af_inet.c:575
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int inet_wait_for_connect(struct sock *sk, long int timeo, int writebias);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81ae32a0)
Location: net/ipv4/af_inet.c:578
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
**Symbols:**

```
ffffffff81ae32a0-ffffffff81ae338a: inet_wait_for_connect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int inet_wait_for_connect(struct sock *sk, long int timeo, int writebias);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81af0680)
Location: net/ipv4/af_inet.c:581
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
**Symbols:**

```
ffffffff81af0680-ffffffff81af0775: inet_wait_for_connect (STB_LOCAL)
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
In net/ipv4/af_inet.c (ffffffff81adbf0b)
Location: net/ipv4/af_inet.c:584
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
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
In net/ipv4/af_inet.c (ffffffff81b9b140)
Location: net/ipv4/af_inet.c:584
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
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
In net/ipv4/af_inet.c (ffffffff81d2cf93)
Location: net/ipv4/af_inet.c:580
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long int inet_wait_for_connect(struct sock *sk, long int timeo, int writebias);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/af_inet.c (0)
Location: net/ipv4/af_inet.c:586
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
**Symbols:**

```
ffffffff81ef4880-ffffffff81ef4991: inet_wait_for_connect (STB_LOCAL)
ffffffff820b0669-ffffffff820b0683: inet_wait_for_connect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long int inet_wait_for_connect(struct sock *sk, long int timeo, int writebias);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/af_inet.c (0)
Location: net/ipv4/af_inet.c:584
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
**Symbols:**

```
ffffffff81f54200-ffffffff81f5431c: inet_wait_for_connect (STB_LOCAL)
ffffffff821318d4-ffffffff821318ed: inet_wait_for_connect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long int inet_wait_for_connect(struct sock *sk, long int timeo, int writebias);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/af_inet.c (0)
Location: net/ipv4/af_inet.c:597
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
```
**Symbols:**

```
ffffffff8201a450-ffffffff8201a55a: inet_wait_for_connect (STB_LOCAL)
ffffffff82213247-ffffffff82213260: inet_wait_for_connect.cold (STB_LOCAL)
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
In net/ipv4/af_inet.c (ffff800010cab378)
Location: net/ipv4/af_inet.c:575
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
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
In net/ipv4/af_inet.c (c0db7dbc)
Location: net/ipv4/af_inet.c:575
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
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
In net/ipv4/af_inet.c (c000000000dbfb48)
Location: net/ipv4/af_inet.c:575
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
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
In net/ipv4/af_inet.c (ffffffe000804d12)
Location: net/ipv4/af_inet.c:575
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
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
In net/ipv4/af_inet.c (ffffffff81993bf2)
Location: net/ipv4/af_inet.c:575
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
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
In net/ipv4/af_inet.c (ffffffff8194d6b2)
Location: net/ipv4/af_inet.c:575
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
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
In net/ipv4/af_inet.c (ffffffff819fe492)
Location: net/ipv4/af_inet.c:575
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
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
In net/ipv4/af_inet.c (ffffffff81a08822)
Location: net/ipv4/af_inet.c:575
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_stream_connect
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
