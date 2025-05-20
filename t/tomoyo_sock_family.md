# Function: <code>tomoyo_sock_family</code>

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
In security/tomoyo/network.c (ffffffff81372382)
Location: security/tomoyo/network.c:621
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
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
In security/tomoyo/network.c (ffffffff813a8a5c)
Location: security/tomoyo/network.c:621
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
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
In security/tomoyo/network.c (ffffffff813bf5ec)
Location: security/tomoyo/network.c:621
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/tomoyo/network.c (ffffffff813d5ec1)
Location: security/tomoyo/network.c:621
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
Direct callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
**Symbols:**

```
ffffffff813d5600-ffffffff813d562f: tomoyo_sock_family.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/tomoyo/network.c (ffffffff813fc3e1)
Location: security/tomoyo/network.c:622
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
Direct callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
**Symbols:**

```
ffffffff813fbb10-ffffffff813fbb3f: tomoyo_sock_family.part.0 (STB_LOCAL)
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
In security/tomoyo/network.c (ffffffff8142d31c)
Location: security/tomoyo/network.c:622
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
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
In security/tomoyo/network.c (ffffffff81449c6c)
Location: security/tomoyo/network.c:622
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
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
In security/tomoyo/network.c (ffffffff814778cc)
Location: security/tomoyo/network.c:626
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
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
In security/tomoyo/network.c (ffffffff8149166c)
Location: security/tomoyo/network.c:626
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
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
In security/tomoyo/network.c (ffffffff814e8a3c)
Location: security/tomoyo/network.c:626
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
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
In security/tomoyo/network.c (ffffffff81505dbc)
Location: security/tomoyo/network.c:626
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
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
In security/tomoyo/network.c (ffffffff8150c8f0)
Location: security/tomoyo/network.c:626
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
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
In security/tomoyo/network.c (ffffffff8156a420)
Location: security/tomoyo/network.c:626
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
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
In security/tomoyo/network.c (ffffffff816063b5)
Location: security/tomoyo/network.c:626
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
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
In security/tomoyo/network.c (ffffffff816b7815)
Location: security/tomoyo/network.c:626
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
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
In security/tomoyo/network.c (ffffffff816f01e5)
Location: security/tomoyo/network.c:626
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
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
In security/tomoyo/network.c (ffffffff8172cfb5)
Location: security/tomoyo/network.c:626
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
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
In security/tomoyo/network.c (ffff800010585ce8)
Location: security/tomoyo/network.c:626
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/tomoyo/network.c (c0737674)
Location: security/tomoyo/network.c:626
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
Direct callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
**Symbols:**

```
c07369b4-c07369e0: tomoyo_sock_family.part.0 (STB_LOCAL)
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
In security/tomoyo/network.c (c0000000006f5898)
Location: security/tomoyo/network.c:626
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
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
In security/tomoyo/network.c (ffffffe0003d576a)
Location: security/tomoyo/network.c:626
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
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
In security/tomoyo/network.c (ffffffff81489c4c)
Location: security/tomoyo/network.c:626
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
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
In security/tomoyo/network.c (ffffffff8147a66c)
Location: security/tomoyo/network.c:626
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
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
In security/tomoyo/network.c (ffffffff81485cec)
Location: security/tomoyo/network.c:626
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
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
In security/tomoyo/network.c (ffffffff8149d82c)
Location: security/tomoyo/network.c:626
Inline: True
Inline callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
</details>
</li>
</ul>

## Differences
