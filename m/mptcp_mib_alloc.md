# Function: <code>mptcp_mib_alloc</code>

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
bool mptcp_mib_alloc(struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/mib.c (ffffffff81bb2cf0)
Location: net/mptcp/mib.c:33
Inline: False
```
**Symbols:**

```
ffffffff81bb2cf0-ffffffff81bb2d44: mptcp_mib_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool mptcp_mib_alloc(struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/mib.c (ffffffff81bc7120)
Location: net/mptcp/mib.c:42
Inline: False
```
**Symbols:**

```
ffffffff81bc7120-ffffffff81bc7174: mptcp_mib_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool mptcp_mib_alloc(struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/mib.c (ffffffff81bb7e50)
Location: net/mptcp/mib.c:54
Inline: False
```
**Symbols:**

```
ffffffff81bb7e50-ffffffff81bb7ea4: mptcp_mib_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool mptcp_mib_alloc(struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/mib.c (ffffffff81c873b0)
Location: net/mptcp/mib.c:62
Inline: False
```
**Symbols:**

```
ffffffff81c873b0-ffffffff81c87404: mptcp_mib_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool mptcp_mib_alloc(struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/mib.c (ffffffff81e2dc00)
Location: net/mptcp/mib.c:71
Inline: False
```
**Symbols:**

```
ffffffff81e2dc00-ffffffff81e2dc50: mptcp_mib_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool mptcp_mib_alloc(struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/mib.c (ffffffff820061b0)
Location: net/mptcp/mib.c:71
Inline: False
```
**Symbols:**

```
ffffffff820061b0-ffffffff82006200: mptcp_mib_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool mptcp_mib_alloc(struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/mib.c (ffffffff82082530)
Location: net/mptcp/mib.c:77
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_init_sock
```
**Symbols:**

```
ffffffff82082530-ffffffff82082580: mptcp_mib_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool mptcp_mib_alloc(struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/mib.c (ffffffff82157ba0)
Location: net/mptcp/mib.c:78
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_init_sock
```
**Symbols:**

```
ffffffff82157ba0-ffffffff82157bf0: mptcp_mib_alloc (STB_GLOBAL)
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
