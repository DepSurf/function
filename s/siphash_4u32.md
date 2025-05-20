# Function: <code>siphash_4u32</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/syncookies.c (ffffffff8186db9d)
Location: include/linux/siphash.h:44
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_hash
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
In net/ipv4/syncookies.c (ffffffff818ee4b9)
Location: include/linux/siphash.h:44
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_hash
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
In net/ipv4/syncookies.c (ffffffff81944e48)
Location: include/linux/siphash.h:44
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_hash
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
In net/ipv4/syncookies.c (ffffffff81975138)
Location: include/linux/siphash.h:44
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_hash
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
In net/ipv4/syncookies.c (ffffffff819dece8)
Location: include/linux/siphash.h:49
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_hash
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
In net/ipv4/syncookies.c (ffffffff81a15d88)
Location: include/linux/siphash.h:49
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_hash
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
In net/ipv4/syncookies.c (ffffffff81b06df8)
Location: include/linux/siphash.h:49
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_hash
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
In net/ipv4/syncookies.c (ffffffff81b14fe8)
Location: include/linux/siphash.h:49
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_hash
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
In net/ipv4/syncookies.c (ffffffff81b02de8)
Location: include/linux/siphash.h:49
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_hash
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
In net/ipv4/syncookies.c (ffffffff81bc5003)
Location: include/linux/siphash.h:47
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_hash
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
In net/core/secure_seq.c (ffffffff81c06632)
Location: include/linux/siphash.h:48
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
```
```
In net/ipv4/syncookies.c (ffffffff81d5a153)
Location: include/linux/siphash.h:48
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_hash
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
In net/core/secure_seq.c (ffffffff81db5fa2)
Location: include/linux/siphash.h:48
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
```
```
In net/ipv4/syncookies.c (ffffffff81f24543)
Location: include/linux/siphash.h:48
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_hash
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
In net/core/secure_seq.c (ffffffff81e26572)
Location: include/linux/siphash.h:48
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
```
```
In net/ipv4/syncookies.c (ffffffff81f840d3)
Location: include/linux/siphash.h:48
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_hash
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
In net/core/secure_seq.c (ffffffff81ee4502)
Location: include/linux/siphash.h:48
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
```
```
In net/ipv4/syncookies.c (ffffffff8204a783)
Location: include/linux/siphash.h:48
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_hash
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
In net/ipv4/syncookies.c (ffff800010cd19b8)
Location: include/linux/siphash.h:49
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_hash
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
In net/ipv4/syncookies.c (c0ddb834)
Location: include/linux/siphash.h:49
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_hash
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
In net/ipv4/syncookies.c (c000000000defbf8)
Location: include/linux/siphash.h:49
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_hash
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
In net/ipv4/syncookies.c (ffffffe000822e32)
Location: include/linux/siphash.h:49
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_hash
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
In net/ipv4/syncookies.c (ffffffff819b5418)
Location: include/linux/siphash.h:49
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_hash
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
In net/ipv4/syncookies.c (ffffffff81972208)
Location: include/linux/siphash.h:49
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_hash
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
In net/ipv4/syncookies.c (ffffffff81a1fcb8)
Location: include/linux/siphash.h:49
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_hash
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
In net/ipv4/syncookies.c (ffffffff81a2b1b8)
Location: include/linux/siphash.h:49
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_hash
```
</details>
</li>
</ul>

## Differences
