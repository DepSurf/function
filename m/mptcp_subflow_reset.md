# Function: <code>mptcp_subflow_reset</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mptcp_subflow_reset(struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81bc2b70)
Location: net/mptcp/subflow.c:303
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/options.c:check_fully_established
```
**Symbols:**

```
ffffffff81bc2b70-ffffffff81bc2c6f: mptcp_subflow_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mptcp_subflow_reset(struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81bb3010)
Location: net/mptcp/subflow.c:346
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/options.c:check_fully_established
```
**Symbols:**

```
ffffffff81bb3010-ffffffff81bb310b: mptcp_subflow_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mptcp_subflow_reset(struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81c816c0)
Location: net/mptcp/subflow.c:354
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/options.c:check_fully_established
```
**Symbols:**

```
ffffffff81c816c0-ffffffff81c817bb: mptcp_subflow_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mptcp_subflow_reset(struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81e27150)
Location: net/mptcp/subflow.c:354
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/options.c:check_fully_established
```
**Symbols:**

```
ffffffff81e27150-ffffffff81e27268: mptcp_subflow_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mptcp_subflow_reset(struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81ffe8c0)
Location: net/mptcp/subflow.c:394
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/options.c:check_fully_established
```
**Symbols:**

```
ffffffff81ffe8c0-ffffffff81ffe9d8: mptcp_subflow_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mptcp_subflow_reset(struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff8207a9d0)
Location: net/mptcp/subflow.c:395
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/options.c:check_fully_established
```
**Symbols:**

```
ffffffff8207a9d0-ffffffff8207aab9: mptcp_subflow_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mptcp_subflow_reset(struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff8214fe30)
Location: net/mptcp/subflow.c:395
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/options.c:check_fully_established
```
**Symbols:**

```
ffffffff8214fe30-ffffffff8214ff19: mptcp_subflow_reset (STB_GLOBAL)
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
