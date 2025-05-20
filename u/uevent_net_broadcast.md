# Function: <code>uevent_net_broadcast</code>

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
In lib/kobject_uevent.c (ffffffff819d1aa8)
Location: lib/kobject_uevent.c:676
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
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
In lib/kobject_uevent.c (ffffffff81a0b9a8)
Location: lib/kobject_uevent.c:678
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
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
In lib/kobject_uevent.c (ffffffff81a7b388)
Location: lib/kobject_uevent.c:681
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
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
In lib/kobject_uevent.c (ffffffff81ab26e8)
Location: lib/kobject_uevent.c:681
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int uevent_net_broadcast(struct sock *usk, struct sk_buff *skb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff815ecc40)
Location: lib/kobject_uevent.c:681
Inline: False
Direct callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
**Symbols:**

```
ffffffff815ecc40-ffffffff815ecd8c: uevent_net_broadcast (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int uevent_net_broadcast(struct sock *usk, struct sk_buff *skb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject_uevent.c (ffffffff81611420)
Location: lib/kobject_uevent.c:681
Inline: False
Direct callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
```
**Symbols:**

```
ffffffff81611420-ffffffff8161156c: uevent_net_broadcast (STB_LOCAL)
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
In lib/kobject_uevent.c (ffffffff815f4b58)
Location: lib/kobject_uevent.c:682
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
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
In lib/kobject_uevent.c (ffffffff81661f28)
Location: lib/kobject_uevent.c:682
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
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
In lib/kobject_uevent.c (ffffffff8177bc48)
Location: lib/kobject_uevent.c:682
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
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
In lib/kobject_uevent.c (ffffffff82024eb8)
Location: lib/kobject_uevent.c:682
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
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
In lib/kobject_uevent.c (ffffffff820a4fc8)
Location: lib/kobject_uevent.c:682
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
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
In lib/kobject_uevent.c (ffffffff8217d128)
Location: lib/kobject_uevent.c:682
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
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
In lib/kobject_uevent.c (ffff800010d8ca48)
Location: lib/kobject_uevent.c:681
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
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
In lib/kobject_uevent.c (c0e86e18)
Location: lib/kobject_uevent.c:681
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
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
In lib/kobject_uevent.c (c000000000ecdb88)
Location: lib/kobject_uevent.c:681
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
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
In lib/kobject_uevent.c (ffffffe0008b50d4)
Location: lib/kobject_uevent.c:681
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
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
In lib/kobject_uevent.c (ffffffff81a51538)
Location: lib/kobject_uevent.c:681
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
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
In lib/kobject_uevent.c (ffffffff81a0e638)
Location: lib/kobject_uevent.c:681
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
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
In lib/kobject_uevent.c (ffffffff81abd928)
Location: lib/kobject_uevent.c:681
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
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
In lib/kobject_uevent.c (ffffffff81ac9da8)
Location: lib/kobject_uevent.c:681
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_rcv_skb
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
