# Function: <code>mptcp_net_exit</code>

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
void mptcp_net_exit(struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/ctrl.c (ffffffff81bb21e0)
Location: net/mptcp/ctrl.c:99
Inline: False
```
**Symbols:**

```
ffffffff81bb21e0-ffffffff81bb2216: mptcp_net_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mptcp_net_exit(struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/ctrl.c (ffffffff81bc64e0)
Location: net/mptcp/ctrl.c:113
Inline: False
```
**Symbols:**

```
ffffffff81bc64e0-ffffffff81bc651c: mptcp_net_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mptcp_net_exit(struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/ctrl.c (ffffffff81bb7040)
Location: net/mptcp/ctrl.c:113
Inline: False
```
**Symbols:**

```
ffffffff81bb7040-ffffffff81bb707c: mptcp_net_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mptcp_net_exit(struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/ctrl.c (ffffffff81c862d0)
Location: net/mptcp/ctrl.c:177
Inline: False
```
**Symbols:**

```
ffffffff81c862d0-ffffffff81c8630c: mptcp_net_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mptcp_net_exit(struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/ctrl.c (ffffffff81e2c660)
Location: net/mptcp/ctrl.c:198
Inline: False
```
**Symbols:**

```
ffffffff81e2c660-ffffffff81e2c6ac: mptcp_net_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mptcp_net_exit(struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/ctrl.c (ffffffff820048f0)
Location: net/mptcp/ctrl.c:198
Inline: False
```
**Symbols:**

```
ffffffff820048f0-ffffffff8200493c: mptcp_net_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mptcp_net_exit(struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/ctrl.c (ffffffff82080a90)
Location: net/mptcp/ctrl.c:198
Inline: False
```
**Symbols:**

```
ffffffff82080a90-ffffffff82080adc: mptcp_net_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mptcp_net_exit(struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/ctrl.c (ffffffff82155ff0)
Location: net/mptcp/ctrl.c:229
Inline: False
```
**Symbols:**

```
ffffffff82155ff0-ffffffff8215603c: mptcp_net_exit (STB_LOCAL)
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
