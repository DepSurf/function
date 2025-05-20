# Function: <code>mctp_addr_notify</code>

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
void mctp_addr_notify(struct mctp_dev *mdev, mctp_eid_t eid, int msg_type, struct sk_buff *req_skb, struct nlmsghdr *req_nlh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mctp/device.c (ffffffff81e38010)
Location: net/mctp/device.c:159
Inline: False
Direct callers:
  - net/mctp/device.c:mctp_rtm_deladdr
  - net/mctp/device.c:mctp_rtm_newaddr
```
**Symbols:**

```
ffffffff81e38010-ffffffff81e38110: mctp_addr_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mctp_addr_notify(struct mctp_dev *mdev, mctp_eid_t eid, int msg_type, struct sk_buff *req_skb, struct nlmsghdr *req_nlh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mctp/device.c (ffffffff82011250)
Location: net/mctp/device.c:159
Inline: False
Direct callers:
  - net/mctp/device.c:mctp_rtm_deladdr
  - net/mctp/device.c:mctp_rtm_newaddr
```
**Symbols:**

```
ffffffff82011250-ffffffff82011350: mctp_addr_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mctp_addr_notify(struct mctp_dev *mdev, mctp_eid_t eid, int msg_type, struct sk_buff *req_skb, struct nlmsghdr *req_nlh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mctp/device.c (ffffffff8208e010)
Location: net/mctp/device.c:159
Inline: False
Direct callers:
  - net/mctp/device.c:mctp_rtm_deladdr
  - net/mctp/device.c:mctp_rtm_newaddr
```
**Symbols:**

```
ffffffff8208e010-ffffffff8208e110: mctp_addr_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mctp_addr_notify(struct mctp_dev *mdev, mctp_eid_t eid, int msg_type, struct sk_buff *req_skb, struct nlmsghdr *req_nlh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mctp/device.c (ffffffff821644d0)
Location: net/mctp/device.c:159
Inline: False
Direct callers:
  - net/mctp/device.c:mctp_rtm_deladdr
  - net/mctp/device.c:mctp_rtm_newaddr
```
**Symbols:**

```
ffffffff821644d0-ffffffff821645d0: mctp_addr_notify (STB_LOCAL)
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
