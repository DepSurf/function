# Function: <code>validate_data_csum</code>

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
enum mapping_status validate_data_csum(struct sock *ssk, struct sk_buff *skb, bool csum_reqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81c808f0)
Location: net/mptcp/subflow.c:844
Inline: False
Direct callers:
  - net/mptcp/subflow.c:get_mapping_status
```
**Symbols:**

```
ffffffff81c808f0-ffffffff81c80b2b: validate_data_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
enum mapping_status validate_data_csum(struct sock *ssk, struct sk_buff *skb, bool csum_reqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81e25b20)
Location: net/mptcp/subflow.c:891
Inline: False
Direct callers:
  - net/mptcp/subflow.c:get_mapping_status
```
**Symbols:**

```
ffffffff81e25b20-ffffffff81e25cbd: validate_data_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
enum mapping_status validate_data_csum(struct sock *ssk, struct sk_buff *skb, bool csum_reqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81ffd7b0)
Location: net/mptcp/subflow.c:963
Inline: False
Direct callers:
  - net/mptcp/subflow.c:get_mapping_status
```
**Symbols:**

```
ffffffff81ffd7b0-ffffffff81ffd94d: validate_data_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
enum mapping_status validate_data_csum(struct sock *ssk, struct sk_buff *skb, bool csum_reqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff82079a80)
Location: net/mptcp/subflow.c:939
Inline: False
Direct callers:
  - net/mptcp/subflow.c:get_mapping_status
```
**Symbols:**

```
ffffffff82079a80-ffffffff82079c1d: validate_data_csum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
enum mapping_status validate_data_csum(struct sock *ssk, struct sk_buff *skb, bool csum_reqd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff8214eee0)
Location: net/mptcp/subflow.c:964
Inline: False
Direct callers:
  - net/mptcp/subflow.c:get_mapping_status
```
**Symbols:**

```
ffffffff8214eee0-ffffffff8214f07d: validate_data_csum (STB_LOCAL)
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
