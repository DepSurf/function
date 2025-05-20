# Function: <code>ip_frag_reinit</code>

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
In net/ipv4/ip_fragment.c (ffffffff81759b8c)
Location: net/ipv4/ip_fragment.c:302
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
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
In net/ipv4/ip_fragment.c (ffffffff817c5f35)
Location: net/ipv4/ip_fragment.c:300
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
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
In net/ipv4/ip_fragment.c (ffffffff817f5a35)
Location: net/ipv4/ip_fragment.c:300
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
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
In net/ipv4/ip_fragment.c (ffffffff81815e6c)
Location: net/ipv4/ip_fragment.c:309
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
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
In net/ipv4/ip_fragment.c (ffffffff81895085)
Location: net/ipv4/ip_fragment.c:311
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
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
In net/ipv4/ip_fragment.c (ffffffff818e91cc)
Location: net/ipv4/ip_fragment.c:246
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
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
In net/ipv4/ip_fragment.c (ffffffff81916283)
Location: net/ipv4/ip_fragment.c:318
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_defrag
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
In net/ipv4/ip_fragment.c (ffffffff819784ad)
Location: net/ipv4/ip_fragment.c:247
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
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
In net/ipv4/ip_fragment.c (ffffffff819aee1d)
Location: net/ipv4/ip_fragment.c:247
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ip_frag_reinit(struct ipq *qp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_fragment.c (ffffffff81a98e50)
Location: net/ipv4/ip_fragment.c:247
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
**Symbols:**

```
ffffffff81a98e50-ffffffff81a98f1c: ip_frag_reinit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ip_frag_reinit(struct ipq *qp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_fragment.c (ffffffff81aa2dc0)
Location: net/ipv4/ip_fragment.c:247
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
```
**Symbols:**

```
ffffffff81aa2dc0-ffffffff81aa2e8c: ip_frag_reinit (STB_LOCAL)
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
In net/ipv4/ip_fragment.c (ffffffff81a8e1b5)
Location: net/ipv4/ip_fragment.c:247
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
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
In net/ipv4/ip_fragment.c (ffffffff81b493a5)
Location: net/ipv4/ip_fragment.c:248
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
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
In net/ipv4/ip_fragment.c (ffffffff81cd6a46)
Location: net/ipv4/ip_fragment.c:248
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
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
In net/ipv4/ip_fragment.c (ffffffff81e97037)
Location: net/ipv4/ip_fragment.c:249
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
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
In net/ipv4/ip_fragment.c (ffffffff81ef5828)
Location: net/ipv4/ip_fragment.c:249
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
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
In net/ipv4/ip_fragment.c (ffffffff81fb97d8)
Location: net/ipv4/ip_fragment.c:249
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
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
In net/ipv4/ip_fragment.c (ffff800010c5f9d0)
Location: net/ipv4/ip_fragment.c:247
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
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
In net/ipv4/ip_fragment.c (c0d6eaa4)
Location: net/ipv4/ip_fragment.c:247
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
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
In net/ipv4/ip_fragment.c (c000000000d61fa0)
Location: net/ipv4/ip_fragment.c:247
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
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
In net/ipv4/ip_fragment.c (ffffffe0007c77c8)
Location: net/ipv4/ip_fragment.c:247
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
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
In net/ipv4/ip_fragment.c (ffffffff8194ec8d)
Location: net/ipv4/ip_fragment.c:247
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
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
In net/ipv4/ip_fragment.c (ffffffff8190877d)
Location: net/ipv4/ip_fragment.c:247
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
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
In net/ipv4/ip_fragment.c (ffffffff819b945d)
Location: net/ipv4/ip_fragment.c:247
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
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
In net/ipv4/ip_fragment.c (ffffffff819c2d4d)
Location: net/ipv4/ip_fragment.c:247
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
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
