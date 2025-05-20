# Function: <code>mptcp_space</code>

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
void mptcp_space(const struct sock *ssk, int *space, int *full_space);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81baf9f0)
Location: net/mptcp/subflow.c:880
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_select_window
```
**Symbols:**

```
ffffffff81baf9f0-ffffffff81bafa72: mptcp_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mptcp_space(const struct sock *ssk, int *space, int *full_space);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81bc32c0)
Location: net/mptcp/subflow.c:1008
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_select_window
```
**Symbols:**

```
ffffffff81bc32c0-ffffffff81bc334a: mptcp_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mptcp_space(const struct sock *ssk, int *space, int *full_space);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81bb35f0)
Location: net/mptcp/subflow.c:1105
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_select_window
```
**Symbols:**

```
ffffffff81bb35f0-ffffffff81bb3672: mptcp_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void mptcp_space(const struct sock *ssk, int *space, int *full_space);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/subflow.c (0)
Location: net/mptcp/subflow.c:1232
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_select_window
```
**Symbols:**

```
ffffffff81d43adc-ffffffff81d43b62: mptcp_space.cold (STB_LOCAL)
ffffffff81c81d00-ffffffff81c81db4: mptcp_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void mptcp_space(const struct sock *ssk, int *space, int *full_space);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/subflow.c (0)
Location: net/mptcp/subflow.c:1321
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_select_window
```
**Symbols:**

```
ffffffff81f10636-ffffffff81f106bc: mptcp_space.cold (STB_LOCAL)
ffffffff81e27890-ffffffff81e27952: mptcp_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void mptcp_space(const struct sock *ssk, int *space, int *full_space);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/subflow.c (0)
Location: net/mptcp/subflow.c:1385
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_select_window
```
**Symbols:**

```
ffffffff820b69c5-ffffffff820b6a4b: mptcp_space.cold (STB_LOCAL)
ffffffff81fff760-ffffffff81fff822: mptcp_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void mptcp_space(const struct sock *ssk, int *space, int *full_space);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/subflow.c (0)
Location: net/mptcp/subflow.c:1356
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_select_window
```
**Symbols:**

```
ffffffff82137d39-ffffffff82137dbf: mptcp_space.cold (STB_LOCAL)
ffffffff8207b830-ffffffff8207b8f2: mptcp_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mptcp_space(const struct sock *ssk, int *space, int *full_space);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff82151370)
Location: net/mptcp/subflow.c:1381
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:__tcp_select_window
```
**Symbols:**

```
ffffffff82151370-ffffffff821513e5: mptcp_space (STB_GLOBAL)
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
