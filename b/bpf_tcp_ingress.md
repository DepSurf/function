# Function: <code>bpf_tcp_ingress</code>

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
In kernel/bpf/sockmap.c (ffffffff811cf048)
Location: kernel/bpf/sockmap.c:664
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:bpf_exec_tx_verdict
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
In net/ipv4/tcp_bpf.c (ffffffff81976ff9)
Location: net/ipv4/tcp_bpf.c:158
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
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
In net/ipv4/tcp_bpf.c (ffffffff819e0b18)
Location: net/ipv4/tcp_bpf.c:161
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
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
In net/ipv4/tcp_bpf.c (ffffffff81a17b48)
Location: net/ipv4/tcp_bpf.c:161
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81b087c0)
Location: net/ipv4/tcp_bpf.c:89
Inline: True
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
**Symbols:**

```
ffffffff81b087c0-ffffffff81b08a50: bpf_tcp_ingress.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81b16bc0)
Location: net/ipv4/tcp_bpf.c:93
Inline: True
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
**Symbols:**

```
ffffffff81b16bc0-ffffffff81b16e4a: bpf_tcp_ingress.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81b04aa0)
Location: net/ipv4/tcp_bpf.c:13
Inline: True
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
**Symbols:**

```
ffffffff81b04aa0-ffffffff81b04d46: bpf_tcp_ingress.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81bc7020)
Location: net/ipv4/tcp_bpf.c:13
Inline: True
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
**Symbols:**

```
ffffffff81bc7020-ffffffff81bc75a9: bpf_tcp_ingress.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81d5c470)
Location: net/ipv4/tcp_bpf.c:13
Inline: True
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
**Symbols:**

```
ffffffff81d5c470-ffffffff81d5cac6: bpf_tcp_ingress.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81f269f0)
Location: net/ipv4/tcp_bpf.c:14
Inline: True
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
**Symbols:**

```
ffffffff81f269f0-ffffffff81f2703b: bpf_tcp_ingress.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81f866b0)
Location: net/ipv4/tcp_bpf.c:32
Inline: True
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
**Symbols:**

```
ffffffff81f866b0-ffffffff81f86cfb: bpf_tcp_ingress.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff8204dcc0)
Location: net/ipv4/tcp_bpf.c:32
Inline: True
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
**Symbols:**

```
ffffffff8204dcc0-ffffffff8204e337: bpf_tcp_ingress.isra.0 (STB_LOCAL)
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
In net/ipv4/tcp_bpf.c (ffff800010cd3710)
Location: net/ipv4/tcp_bpf.c:161
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
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
In net/ipv4/tcp_bpf.c (c0ddd5c8)
Location: net/ipv4/tcp_bpf.c:161
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
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
In net/ipv4/tcp_bpf.c (c000000000df27f0)
Location: net/ipv4/tcp_bpf.c:161
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
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
In net/ipv4/tcp_bpf.c (ffffffe00082469a)
Location: net/ipv4/tcp_bpf.c:161
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
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
In net/ipv4/tcp_bpf.c (ffffffff819b71d8)
Location: net/ipv4/tcp_bpf.c:161
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
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
In net/ipv4/tcp_bpf.c (ffffffff81973fc8)
Location: net/ipv4/tcp_bpf.c:161
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
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
In net/ipv4/tcp_bpf.c (ffffffff81a21c58)
Location: net/ipv4/tcp_bpf.c:161
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
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
In net/ipv4/tcp_bpf.c (ffffffff81a2d003)
Location: net/ipv4/tcp_bpf.c:161
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
</details>
</li>
</ul>

## Differences
