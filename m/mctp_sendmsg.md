# Function: <code>mctp_sendmsg</code>

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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mctp_sendmsg(struct socket *sock, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mctp/af_mctp.c (0)
Location: net/mctp/af_mctp.c:93
Inline: False
```
**Symbols:**

```
ffffffff81e370f0-ffffffff81e374a9: mctp_sendmsg (STB_LOCAL)
ffffffff81f10cba-ffffffff81f10ccf: mctp_sendmsg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int mctp_sendmsg(struct socket *sock, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mctp/af_mctp.c (0)
Location: net/mctp/af_mctp.c:93
Inline: False
```
**Symbols:**

```
ffffffff8200ff30-ffffffff820102e9: mctp_sendmsg (STB_LOCAL)
ffffffff820b6f7d-ffffffff820b6f92: mctp_sendmsg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int mctp_sendmsg(struct socket *sock, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mctp/af_mctp.c (0)
Location: net/mctp/af_mctp.c:93
Inline: False
```
**Symbols:**

```
ffffffff8208cb50-ffffffff8208cfd6: mctp_sendmsg (STB_LOCAL)
ffffffff821382a4-ffffffff82138300: mctp_sendmsg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int mctp_sendmsg(struct socket *sock, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mctp/af_mctp.c (0)
Location: net/mctp/af_mctp.c:93
Inline: False
```
**Symbols:**

```
ffffffff82163020-ffffffff821634a0: mctp_sendmsg (STB_LOCAL)
ffffffff8221a141-ffffffff8221a19d: mctp_sendmsg.cold (STB_LOCAL)
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
