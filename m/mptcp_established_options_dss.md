# Function: <code>mptcp_established_options_dss</code>

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
In net/mptcp/options.c (ffffffff81bb0b60)
Location: net/mptcp/options.c:474
Inline: True
Direct callers:
  - net/mptcp/options.c:mptcp_established_options
```
**Symbols:**

```
ffffffff81bb0b60-ffffffff81bb0d0f: mptcp_established_options_dss.constprop.0 (STB_LOCAL)
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
In net/mptcp/options.c (ffffffff81bc49d0)
Location: net/mptcp/options.c:496
Inline: True
Direct callers:
  - net/mptcp/options.c:mptcp_established_options
```
**Symbols:**

```
ffffffff81bc49d0-ffffffff81bc4be5: mptcp_established_options_dss.constprop.0 (STB_LOCAL)
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
In net/mptcp/options.c (ffffffff81bb5050)
Location: net/mptcp/options.c:527
Inline: True
Direct callers:
  - net/mptcp/options.c:mptcp_established_options
```
**Symbols:**

```
ffffffff81bb5050-ffffffff81bb525b: mptcp_established_options_dss.constprop.0 (STB_LOCAL)
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
In net/mptcp/options.c (0)
Location: net/mptcp/options.c:549
Inline: True
Direct callers:
  - net/mptcp/options.c:mptcp_established_options
```
**Symbols:**

```
ffffffff81c83890-ffffffff81c83b59: mptcp_established_options_dss.constprop.0 (STB_LOCAL)
ffffffff81d43cf7-ffffffff81d43dd9: mptcp_established_options_dss.constprop.0.cold (STB_LOCAL)
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
In net/mptcp/options.c (0)
Location: net/mptcp/options.c:551
Inline: True
Direct callers:
  - net/mptcp/options.c:mptcp_established_options
```
**Symbols:**

```
ffffffff81e29860-ffffffff81e29b2c: mptcp_established_options_dss.constprop.0 (STB_LOCAL)
ffffffff81f10829-ffffffff81f1090b: mptcp_established_options_dss.constprop.0.cold (STB_LOCAL)
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
In net/mptcp/options.c (0)
Location: net/mptcp/options.c:556
Inline: True
Direct callers:
  - net/mptcp/options.c:mptcp_established_options
```
**Symbols:**

```
ffffffff82001950-ffffffff82001c1c: mptcp_established_options_dss.constprop.0 (STB_LOCAL)
ffffffff820b6b98-ffffffff820b6c7a: mptcp_established_options_dss.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool mptcp_established_options_dss(struct sock *sk, struct sk_buff *skb, bool snd_data_fin_enable, unsigned int *size, struct mptcp_out_options *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/options.c (0)
Location: net/mptcp/options.c:555
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_established_options
```
**Symbols:**

```
ffffffff8207de10-ffffffff8207e0dc: mptcp_established_options_dss (STB_LOCAL)
ffffffff82137f5f-ffffffff82138041: mptcp_established_options_dss.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool mptcp_established_options_dss(struct sock *sk, struct sk_buff *skb, bool snd_data_fin_enable, unsigned int *size, struct mptcp_out_options *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/options.c (0)
Location: net/mptcp/options.c:556
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_established_options
```
**Symbols:**

```
ffffffff82153320-ffffffff821535c6: mptcp_established_options_dss (STB_LOCAL)
ffffffff82219dd4-ffffffff82219e57: mptcp_established_options_dss.cold (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
