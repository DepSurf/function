# Function: <code>raw_err</code>

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
In net/ipv4/raw.c (ffffffff81785858)
Location: net/ipv4/raw.c:223
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
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
In net/ipv4/raw.c (ffffffff817f2e56)
Location: net/ipv4/raw.c:225
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
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
In net/ipv4/raw.c (ffffffff81823c36)
Location: net/ipv4/raw.c:227
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
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
In net/ipv4/raw.c (ffffffff81844916)
Location: net/ipv4/raw.c:227
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
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
In net/ipv4/raw.c (ffffffff818c4351)
Location: net/ipv4/raw.c:230
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
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
In net/ipv4/raw.c (ffffffff8191a07d)
Location: net/ipv4/raw.c:230
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
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
In net/ipv4/raw.c (ffffffff819488e5)
Location: net/ipv4/raw.c:229
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
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
In net/ipv4/raw.c (ffffffff819acf69)
Location: net/ipv4/raw.c:225
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
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
In net/ipv4/raw.c (ffffffff819e3c39)
Location: net/ipv4/raw.c:225
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void raw_err(struct sock *sk, struct sk_buff *skb, u32 info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff81acf9a0)
Location: net/ipv4/raw.c:225
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_icmp_error
```
**Symbols:**

```
ffffffff81acf9a0-ffffffff81acfb88: raw_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void raw_err(struct sock *sk, struct sk_buff *skb, u32 info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff81adb920)
Location: net/ipv4/raw.c:225
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_icmp_error
```
**Symbols:**

```
ffffffff81adb920-ffffffff81adbb08: raw_err (STB_LOCAL)
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
In net/ipv4/raw.c (ffffffff81ac8443)
Location: net/ipv4/raw.c:225
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
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
In net/ipv4/raw.c (ffffffff81b86cb3)
Location: net/ipv4/raw.c:225
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
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
In net/ipv4/raw.c (ffffffff81d178ee)
Location: net/ipv4/raw.c:201
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
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
In net/ipv4/raw.c (ffffffff81ede1ae)
Location: net/ipv4/raw.c:201
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
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
In net/ipv4/raw.c (ffffffff81f3d4b4)
Location: net/ipv4/raw.c:201
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
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
In net/ipv4/raw.c (ffffffff82003612)
Location: net/ipv4/raw.c:201
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
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
In net/ipv4/raw.c (ffff800010c98608)
Location: net/ipv4/raw.c:225
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
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
In net/ipv4/raw.c (c0da6464)
Location: net/ipv4/raw.c:225
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
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
In net/ipv4/raw.c (c000000000da9c90)
Location: net/ipv4/raw.c:225
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
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
In net/ipv4/raw.c (ffffffe0007f67d2)
Location: net/ipv4/raw.c:225
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
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
In net/ipv4/raw.c (ffffffff81983aa9)
Location: net/ipv4/raw.c:225
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
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
In net/ipv4/raw.c (ffffffff8193d569)
Location: net/ipv4/raw.c:225
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
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
In net/ipv4/raw.c (ffffffff819ee279)
Location: net/ipv4/raw.c:225
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
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
In net/ipv4/raw.c (ffffffff819f82d9)
Location: net/ipv4/raw.c:225
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_icmp_error
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
