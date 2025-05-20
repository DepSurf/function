# Function: <code>mptcp_established_options_mp_fail</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool mptcp_established_options_mp_fail(struct sock *sk, unsigned int *size, unsigned int remaining, struct mptcp_out_options *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff81c829f0)
Location: net/mptcp/options.c:773
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_established_options
  - net/mptcp/options.c:mptcp_established_options
```
**Symbols:**

```
ffffffff81c829f0-ffffffff81c82a43: mptcp_established_options_mp_fail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool mptcp_established_options_mp_fail(struct sock *sk, unsigned int *size, unsigned int remaining, struct mptcp_out_options *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff81e28880)
Location: net/mptcp/options.c:796
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_established_options
  - net/mptcp/options.c:mptcp_established_options
```
**Symbols:**

```
ffffffff81e28880-ffffffff81e28907: mptcp_established_options_mp_fail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool mptcp_established_options_mp_fail(struct sock *sk, unsigned int *size, unsigned int remaining, struct mptcp_out_options *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff820008c0)
Location: net/mptcp/options.c:801
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_established_options
  - net/mptcp/options.c:mptcp_established_options
```
**Symbols:**

```
ffffffff820008c0-ffffffff82000947: mptcp_established_options_mp_fail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool mptcp_established_options_mp_fail(struct sock *sk, unsigned int *size, unsigned int remaining, struct mptcp_out_options *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff8207ca70)
Location: net/mptcp/options.c:801
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_established_options
  - net/mptcp/options.c:mptcp_established_options
```
**Symbols:**

```
ffffffff8207ca70-ffffffff8207caf7: mptcp_established_options_mp_fail (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool mptcp_established_options_mp_fail(struct sock *sk, unsigned int *size, unsigned int remaining, struct mptcp_out_options *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff82151f70)
Location: net/mptcp/options.c:802
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_established_options
  - net/mptcp/options.c:mptcp_established_options
```
**Symbols:**

```
ffffffff82151f70-ffffffff82151ff7: mptcp_established_options_mp_fail (STB_LOCAL)
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
