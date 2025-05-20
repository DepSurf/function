# Function: <code>inet_peer_gc</code>

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
In net/ipv4/inetpeer.c (ffffffff8175817b)
Location: net/ipv4/inetpeer.c:367
Inline: True
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
In net/ipv4/inetpeer.c (ffffffff817c442b)
Location: net/ipv4/inetpeer.c:367
Inline: True
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
In net/ipv4/inetpeer.c (ffffffff817f3f4b)
Location: net/ipv4/inetpeer.c:367
Inline: True
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
In net/ipv4/inetpeer.c (ffffffff81814342)
Location: net/ipv4/inetpeer.c:368
Inline: True
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
In net/ipv4/inetpeer.c (ffffffff81893827)
Location: net/ipv4/inetpeer.c:146
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
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
In net/ipv4/inetpeer.c (ffffffff818e7b96)
Location: net/ipv4/inetpeer.c:147
Inline: True
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
In net/ipv4/inetpeer.c (ffffffff81914a46)
Location: net/ipv4/inetpeer.c:147
Inline: True
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
In net/ipv4/inetpeer.c (ffffffff81976e67)
Location: net/ipv4/inetpeer.c:147
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
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
In net/ipv4/inetpeer.c (ffffffff819ad7f7)
Location: net/ipv4/inetpeer.c:147
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void inet_peer_gc(struct inet_peer_base *base, struct inet_peer **gc_stack, unsigned int gc_cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inetpeer.c (ffffffff81a972d0)
Location: net/ipv4/inetpeer.c:147
Inline: False
Direct callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
**Symbols:**

```
ffffffff81a972d0-ffffffff81a973db: inet_peer_gc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void inet_peer_gc(struct inet_peer_base *base, struct inet_peer **gc_stack, unsigned int gc_cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inetpeer.c (ffffffff81aa1290)
Location: net/ipv4/inetpeer.c:147
Inline: False
Direct callers:
  - net/ipv4/inetpeer.c:inet_getpeer
```
**Symbols:**

```
ffffffff81aa1290-ffffffff81aa139b: inet_peer_gc (STB_LOCAL)
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
In net/ipv4/inetpeer.c (ffffffff81a8c6a6)
Location: net/ipv4/inetpeer.c:140
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
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
In net/ipv4/inetpeer.c (ffffffff81b477e6)
Location: net/ipv4/inetpeer.c:140
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
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
In net/ipv4/inetpeer.c (ffffffff81cd49fb)
Location: net/ipv4/inetpeer.c:140
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
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
In net/ipv4/inetpeer.c (ffffffff81e94cdb)
Location: net/ipv4/inetpeer.c:140
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
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
In net/ipv4/inetpeer.c (ffffffff81ef34ab)
Location: net/ipv4/inetpeer.c:140
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
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
In net/ipv4/inetpeer.c (ffffffff81fb743b)
Location: net/ipv4/inetpeer.c:140
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
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
In net/ipv4/inetpeer.c (ffff800010c5daf8)
Location: net/ipv4/inetpeer.c:147
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
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
In net/ipv4/inetpeer.c (c0d6cebc)
Location: net/ipv4/inetpeer.c:147
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
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
In net/ipv4/inetpeer.c (c000000000d60008)
Location: net/ipv4/inetpeer.c:147
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
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
In net/ipv4/inetpeer.c (ffffffe0007c6324)
Location: net/ipv4/inetpeer.c:147
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
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
In net/ipv4/inetpeer.c (ffffffff8194d667)
Location: net/ipv4/inetpeer.c:147
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
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
In net/ipv4/inetpeer.c (ffffffff81907157)
Location: net/ipv4/inetpeer.c:147
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
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
In net/ipv4/inetpeer.c (ffffffff819b7e37)
Location: net/ipv4/inetpeer.c:147
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
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
In net/ipv4/inetpeer.c (ffffffff819c16b5)
Location: net/ipv4/inetpeer.c:147
Inline: True
Inline callers:
  - net/ipv4/inetpeer.c:inet_getpeer
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
