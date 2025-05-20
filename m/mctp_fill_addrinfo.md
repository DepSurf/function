# Function: <code>mctp_fill_addrinfo</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mctp_fill_addrinfo(struct sk_buff *skb, struct mctp_dev *mdev, mctp_eid_t eid, int msg_type, u32 portid, u32 seq, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mctp/device.c (ffffffff81e37ee0)
Location: net/mctp/device.c:61
Inline: False
Direct callers:
  - net/mctp/device.c:mctp_addr_notify
  - net/mctp/device.c:mctp_dump_addrinfo
```
**Symbols:**

```
ffffffff81e37ee0-ffffffff81e38009: mctp_fill_addrinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mctp_fill_addrinfo(struct sk_buff *skb, struct mctp_dev *mdev, mctp_eid_t eid, int msg_type, u32 portid, u32 seq, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mctp/device.c (ffffffff82011110)
Location: net/mctp/device.c:61
Inline: False
Direct callers:
  - net/mctp/device.c:mctp_addr_notify
  - net/mctp/device.c:mctp_dump_addrinfo
```
**Symbols:**

```
ffffffff82011110-ffffffff82011239: mctp_fill_addrinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mctp_fill_addrinfo(struct sk_buff *skb, struct mctp_dev *mdev, mctp_eid_t eid, int msg_type, u32 portid, u32 seq, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mctp/device.c (ffffffff8208ded0)
Location: net/mctp/device.c:61
Inline: False
Direct callers:
  - net/mctp/device.c:mctp_addr_notify
  - net/mctp/device.c:mctp_dump_addrinfo
```
**Symbols:**

```
ffffffff8208ded0-ffffffff8208dff9: mctp_fill_addrinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mctp_fill_addrinfo(struct sk_buff *skb, struct mctp_dev *mdev, mctp_eid_t eid, int msg_type, u32 portid, u32 seq, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mctp/device.c (ffffffff82164390)
Location: net/mctp/device.c:61
Inline: False
Direct callers:
  - net/mctp/device.c:mctp_addr_notify
  - net/mctp/device.c:mctp_dump_addrinfo
```
**Symbols:**

```
ffffffff82164390-ffffffff821644b9: mctp_fill_addrinfo (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
