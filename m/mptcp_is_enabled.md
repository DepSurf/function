# Function: <code>mptcp_is_enabled</code>

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
int mptcp_is_enabled(struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/ctrl.c (ffffffff81bb2220)
Location: net/mptcp/ctrl.c:28
Inline: False
```
**Symbols:**

```
ffffffff81bb2220-ffffffff81bb223f: mptcp_is_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mptcp_is_enabled(struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/ctrl.c (ffffffff81bc6520)
Location: net/mptcp/ctrl.c:29
Inline: False
```
**Symbols:**

```
ffffffff81bc6520-ffffffff81bc6549: mptcp_is_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mptcp_is_enabled(struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/ctrl.c (ffffffff81bb7080)
Location: net/mptcp/ctrl.c:29
Inline: False
```
**Symbols:**

```
ffffffff81bb7080-ffffffff81bb70a9: mptcp_is_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mptcp_is_enabled(const struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/ctrl.c (ffffffff81c86310)
Location: net/mptcp/ctrl.c:36
Inline: False
```
**Symbols:**

```
ffffffff81c86310-ffffffff81c8633a: mptcp_is_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mptcp_is_enabled(const struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/ctrl.c (ffffffff81e2c6b0)
Location: net/mptcp/ctrl.c:42
Inline: False
```
**Symbols:**

```
ffffffff81e2c6b0-ffffffff81e2c6ea: mptcp_is_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mptcp_is_enabled(const struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/ctrl.c (ffffffff82004950)
Location: net/mptcp/ctrl.c:42
Inline: False
```
**Symbols:**

```
ffffffff82004950-ffffffff8200498a: mptcp_is_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mptcp_is_enabled(const struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/ctrl.c (ffffffff82080af0)
Location: net/mptcp/ctrl.c:42
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_init_sock
```
**Symbols:**

```
ffffffff82080af0-ffffffff82080b2a: mptcp_is_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mptcp_is_enabled(const struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/ctrl.c (ffffffff82156050)
Location: net/mptcp/ctrl.c:44
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_init_sock
```
**Symbols:**

```
ffffffff82156050-ffffffff8215608a: mptcp_is_enabled (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct net *net</code> ➡️ <code>const struct net *net</code>
</li>
</ul>
</details>
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
