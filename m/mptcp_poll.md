# Function: <code>mptcp_poll</code>

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
__poll_t mptcp_poll(struct file *file, struct socket *sock, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81baac10)
Location: net/mptcp/protocol.c:1966
Inline: False
```
**Symbols:**

```
ffffffff81baac10-ffffffff81baad77: mptcp_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
__poll_t mptcp_poll(struct file *file, struct socket *sock, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bbc110)
Location: net/mptcp/protocol.c:3349
Inline: False
```
**Symbols:**

```
ffffffff81bbc110-ffffffff81bbc32e: mptcp_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
__poll_t mptcp_poll(struct file *file, struct socket *sock, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bab1e0)
Location: net/mptcp/protocol.c:3343
Inline: False
```
**Symbols:**

```
ffffffff81bab1e0-ffffffff81bab40a: mptcp_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
__poll_t mptcp_poll(struct file *file, struct socket *sock, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81c77ae0)
Location: net/mptcp/protocol.c:3442
Inline: False
```
**Symbols:**

```
ffffffff81c77ae0-ffffffff81c77d2a: mptcp_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
__poll_t mptcp_poll(struct file *file, struct socket *sock, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81e1cfa0)
Location: net/mptcp/protocol.c:3682
Inline: False
```
**Symbols:**

```
ffffffff81e1cfa0-ffffffff81e1d24a: mptcp_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
__poll_t mptcp_poll(struct file *file, struct socket *sock, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81ff44e0)
Location: net/mptcp/protocol.c:3751
Inline: False
```
**Symbols:**

```
ffffffff81ff44e0-ffffffff81ff47cc: mptcp_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
__poll_t mptcp_poll(struct file *file, struct socket *sock, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff82070e90)
Location: net/mptcp/protocol.c:3806
Inline: False
```
**Symbols:**

```
ffffffff82070e90-ffffffff8207113a: mptcp_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
__poll_t mptcp_poll(struct file *file, struct socket *sock, struct poll_table_struct *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff821454b0)
Location: net/mptcp/protocol.c:3954
Inline: False
```
**Symbols:**

```
ffffffff821454b0-ffffffff821457a6: mptcp_poll (STB_LOCAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
