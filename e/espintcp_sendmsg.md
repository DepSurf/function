# Function: <code>espintcp_sendmsg</code>

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
int espintcp_sendmsg(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/espintcp.c (ffffffff81b22e30)
Location: net/xfrm/espintcp.c:311
Inline: False
```
**Symbols:**

```
ffffffff81b22e30-ffffffff81b230ec: espintcp_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int espintcp_sendmsg(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/espintcp.c (ffffffff81b31820)
Location: net/xfrm/espintcp.c:315
Inline: False
```
**Symbols:**

```
ffffffff81b31820-ffffffff81b31adc: espintcp_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int espintcp_sendmsg(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/espintcp.c (ffffffff81b1f550)
Location: net/xfrm/espintcp.c:315
Inline: False
```
**Symbols:**

```
ffffffff81b1f550-ffffffff81b1f809: espintcp_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int espintcp_sendmsg(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/espintcp.c (ffffffff81be4170)
Location: net/xfrm/espintcp.c:315
Inline: False
```
**Symbols:**

```
ffffffff81be4170-ffffffff81be4448: espintcp_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int espintcp_sendmsg(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/espintcp.c (ffffffff81d7b600)
Location: net/xfrm/espintcp.c:313
Inline: False
```
**Symbols:**

```
ffffffff81d7b600-ffffffff81d7b8fb: espintcp_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int espintcp_sendmsg(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/espintcp.c (ffffffff81f48690)
Location: net/xfrm/espintcp.c:313
Inline: False
```
**Symbols:**

```
ffffffff81f48690-ffffffff81f4898b: espintcp_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int espintcp_sendmsg(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/espintcp.c (ffffffff81fa8500)
Location: net/xfrm/espintcp.c:320
Inline: False
```
**Symbols:**

```
ffffffff81fa8500-ffffffff81fa87fb: espintcp_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int espintcp_sendmsg(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/espintcp.c (ffffffff820757f0)
Location: net/xfrm/espintcp.c:320
Inline: False
```
**Symbols:**

```
ffffffff820757f0-ffffffff82075aeb: espintcp_sendmsg (STB_LOCAL)
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
