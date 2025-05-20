# Function: <code>mptcp_cancel_work</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bab078)
Location: net/mptcp/protocol.c:1306
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_close
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
In net/mptcp/protocol.c (ffffffff81bc01ba)
Location: net/mptcp/protocol.c:2425
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_close
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
In net/mptcp/protocol.c (ffffffff81bb007d)
Location: net/mptcp/protocol.c:2493
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_close
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
In net/mptcp/protocol.c (ffffffff81c7de9c)
Location: net/mptcp/protocol.c:2551
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_close
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
In net/mptcp/protocol.c (ffffffff81e223fe)
Location: net/mptcp/protocol.c:2695
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_close
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void mptcp_cancel_work(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81ffa914)
Location: net/mptcp/protocol.c:2743
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/protocol.c:mptcp_close
Direct callers:
  - net/mptcp/subflow.c:mptcp_subflow_queue_clean
```
**Symbols:**

```
ffffffff81ff92b0-ffffffff81ff9302: mptcp_cancel_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void mptcp_cancel_work(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff820757a0)
Location: net/mptcp/protocol.c:2748
Inline: True
Direct callers:
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/subflow.c:mptcp_subflow_queue_clean
```
**Symbols:**

```
ffffffff820757a0-ffffffff820757f2: mptcp_cancel_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void mptcp_cancel_work(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff82149e10)
Location: net/mptcp/protocol.c:2835
Inline: True
Direct callers:
  - net/mptcp/protocol.c:mptcp_close
  - net/mptcp/subflow.c:mptcp_subflow_queue_clean
```
**Symbols:**

```
ffffffff82149e10-ffffffff82149e62: mptcp_cancel_work (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
