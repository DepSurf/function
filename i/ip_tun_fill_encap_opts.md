# Function: <code>ip_tun_fill_encap_opts</code>

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
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_tunnel_core.c (ffffffff81af9dd7)
Location: net/ipv4/ip_tunnel_core.c:592
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
Direct callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
**Symbols:**

```
ffffffff81af9a00-ffffffff81af9b9b: ip_tun_fill_encap_opts.part.0.constprop.0 (STB_LOCAL)
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
In net/ipv4/ip_tunnel_core.c (ffffffff81b07527)
Location: net/ipv4/ip_tunnel_core.c:808
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
Direct callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
**Symbols:**

```
ffffffff81b07150-ffffffff81b072eb: ip_tun_fill_encap_opts.part.0.constprop.0 (STB_LOCAL)
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
In net/ipv4/ip_tunnel_core.c (ffffffff81af2cd7)
Location: net/ipv4/ip_tunnel_core.c:809
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
Direct callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
**Symbols:**

```
ffffffff81af2720-ffffffff81af2a94: ip_tun_fill_encap_opts.part.0.constprop.0 (STB_LOCAL)
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
In net/ipv4/ip_tunnel_core.c (ffffffff81bb31e7)
Location: net/ipv4/ip_tunnel_core.c:809
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
Direct callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
**Symbols:**

```
ffffffff81bb2c30-ffffffff81bb2fa4: ip_tun_fill_encap_opts.part.0.constprop.0 (STB_LOCAL)
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
In net/ipv4/ip_tunnel_core.c (ffffffff81d46400)
Location: net/ipv4/ip_tunnel_core.c:809
Inline: True
Direct callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
**Symbols:**

```
ffffffff81d46400-ffffffff81d467a3: ip_tun_fill_encap_opts.constprop.0 (STB_LOCAL)
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
In net/ipv4/ip_tunnel_core.c (ffffffff81f0f800)
Location: net/ipv4/ip_tunnel_core.c:809
Inline: True
Direct callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
**Symbols:**

```
ffffffff81f0f800-ffffffff81f0fba3: ip_tun_fill_encap_opts.constprop.0 (STB_LOCAL)
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
In net/ipv4/ip_tunnel_core.c (ffffffff81f6f4f0)
Location: net/ipv4/ip_tunnel_core.c:809
Inline: True
Direct callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
**Symbols:**

```
ffffffff81f6f4f0-ffffffff81f6f893: ip_tun_fill_encap_opts.constprop.0 (STB_LOCAL)
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
In net/ipv4/ip_tunnel_core.c (ffffffff82035c20)
Location: net/ipv4/ip_tunnel_core.c:809
Inline: True
Direct callers:
  - net/ipv4/ip_tunnel_core.c:ip6_tun_fill_encap_info
  - net/ipv4/ip_tunnel_core.c:ip_tun_fill_encap_info
```
**Symbols:**

```
ffffffff82035c20-ffffffff82035fc3: ip_tun_fill_encap_opts.constprop.0 (STB_LOCAL)
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
