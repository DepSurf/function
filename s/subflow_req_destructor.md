# Function: <code>subflow_req_destructor</code>

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
void subflow_req_destructor(struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81baeaa0)
Location: net/mptcp/subflow.c:66
Inline: False
```
**Symbols:**

```
ffffffff81baeaa0-ffffffff81baeb3a: subflow_req_destructor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void subflow_req_destructor(struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81bc1600)
Location: net/mptcp/subflow.c:33
Inline: False
```
**Symbols:**

```
ffffffff81bc1600-ffffffff81bc1688: subflow_req_destructor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void subflow_req_destructor(struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81bb1eb0)
Location: net/mptcp/subflow.c:38
Inline: False
```
**Symbols:**

```
ffffffff81bb1eb0-ffffffff81bb1f38: subflow_req_destructor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void subflow_req_destructor(struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81c80140)
Location: net/mptcp/subflow.c:38
Inline: False
```
**Symbols:**

```
ffffffff81c80140-ffffffff81c801c5: subflow_req_destructor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void subflow_req_destructor(struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81e25dc0)
Location: net/mptcp/subflow.c:38
Inline: False
```
**Symbols:**

```
ffffffff81e25dc0-ffffffff81e25e4f: subflow_req_destructor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void subflow_req_destructor(struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81ffd960)
Location: net/mptcp/subflow.c:38
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_v6_req_destructor
  - net/mptcp/subflow.c:subflow_v4_req_destructor
```
**Symbols:**

```
ffffffff81ffd960-ffffffff81ffd9f8: subflow_req_destructor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void subflow_req_destructor(struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff82079c30)
Location: net/mptcp/subflow.c:39
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_v6_req_destructor
  - net/mptcp/subflow.c:subflow_v4_req_destructor
```
**Symbols:**

```
ffffffff82079c30-ffffffff82079cc8: subflow_req_destructor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void subflow_req_destructor(struct request_sock *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff8214f090)
Location: net/mptcp/subflow.c:39
Inline: False
Direct callers:
  - net/mptcp/subflow.c:subflow_v6_req_destructor
  - net/mptcp/subflow.c:subflow_v4_req_destructor
```
**Symbols:**

```
ffffffff8214f090-ffffffff8214f128: subflow_req_destructor (STB_LOCAL)
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
