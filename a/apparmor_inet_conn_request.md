# Function: <code>apparmor_inet_conn_request</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int apparmor_inet_conn_request(struct sock *sk, struct sk_buff *skb, struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff814ffc30)
Location: security/apparmor/lsm.c:1264
Inline: False
```
**Symbols:**

```
ffffffff814ffc30-ffffffff814ffc71: apparmor_inet_conn_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int apparmor_inet_conn_request(const struct sock *sk, struct sk_buff *skb, struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8151ce20)
Location: security/apparmor/lsm.c:1264
Inline: False
```
**Symbols:**

```
ffffffff8151ce20-ffffffff8151ce61: apparmor_inet_conn_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int apparmor_inet_conn_request(const struct sock *sk, struct sk_buff *skb, struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff81523630)
Location: security/apparmor/lsm.c:1273
Inline: False
```
**Symbols:**

```
ffffffff81523630-ffffffff81523671: apparmor_inet_conn_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int apparmor_inet_conn_request(const struct sock *sk, struct sk_buff *skb, struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff81581810)
Location: security/apparmor/lsm.c:1273
Inline: False
```
**Symbols:**

```
ffffffff81581810-ffffffff81581851: apparmor_inet_conn_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int apparmor_inet_conn_request(const struct sock *sk, struct sk_buff *skb, struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff81620bd0)
Location: security/apparmor/lsm.c:1492
Inline: False
```
**Symbols:**

```
ffffffff81620bd0-ffffffff81620c2f: apparmor_inet_conn_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int apparmor_inet_conn_request(const struct sock *sk, struct sk_buff *skb, struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff816d4310)
Location: security/apparmor/lsm.c:1548
Inline: False
```
**Symbols:**

```
ffffffff816d4310-ffffffff816d436f: apparmor_inet_conn_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int apparmor_inet_conn_request(const struct sock *sk, struct sk_buff *skb, struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8170d2a0)
Location: security/apparmor/lsm.c:1698
Inline: False
```
**Symbols:**

```
ffffffff8170d2a0-ffffffff8170d2ff: apparmor_inet_conn_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int apparmor_inet_conn_request(const struct sock *sk, struct sk_buff *skb, struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/apparmor/lsm.c (0)
Location: security/apparmor/lsm.c:1716
Inline: False
```
**Symbols:**

```
ffffffff8174bae0-ffffffff8174bb79: apparmor_inet_conn_request (STB_LOCAL)
ffffffff821d1cde-ffffffff821d1cfb: apparmor_inet_conn_request.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct sock *sk</code> ➡️ <code>const struct sock *sk</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
