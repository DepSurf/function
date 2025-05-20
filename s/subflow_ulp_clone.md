# Function: <code>subflow_ulp_clone</code>

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
void subflow_ulp_clone(const struct request_sock *req, struct sock *newsk, const gfp_t priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81badfb0)
Location: net/mptcp/subflow.c:1184
Inline: False
```
**Symbols:**

```
ffffffff81badfb0-ffffffff81bae13d: subflow_ulp_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void subflow_ulp_clone(const struct request_sock *req, struct sock *newsk, const gfp_t priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81bc0f90)
Location: net/mptcp/subflow.c:1434
Inline: False
```
**Symbols:**

```
ffffffff81bc0f90-ffffffff81bc1145: subflow_ulp_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void subflow_ulp_clone(const struct request_sock *req, struct sock *newsk, const gfp_t priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81bb14b0)
Location: net/mptcp/subflow.c:1572
Inline: False
```
**Symbols:**

```
ffffffff81bb14b0-ffffffff81bb1693: subflow_ulp_clone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void subflow_ulp_clone(const struct request_sock *req, struct sock *newsk, const gfp_t priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/subflow.c (0)
Location: net/mptcp/subflow.c:1702
Inline: False
```
**Symbols:**

```
ffffffff81c7f660-ffffffff81c7f879: subflow_ulp_clone (STB_LOCAL)
ffffffff81d43943-ffffffff81d4395e: subflow_ulp_clone.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void subflow_ulp_clone(const struct request_sock *req, struct sock *newsk, const gfp_t priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/subflow.c (0)
Location: net/mptcp/subflow.c:1843
Inline: False
```
**Symbols:**

```
ffffffff81e24f10-ffffffff81e25139: subflow_ulp_clone (STB_LOCAL)
ffffffff81f1044a-ffffffff81f10465: subflow_ulp_clone.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void subflow_ulp_clone(const struct request_sock *req, struct sock *newsk, const gfp_t priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/subflow.c (0)
Location: net/mptcp/subflow.c:1940
Inline: False
```
**Symbols:**

```
ffffffff81ffcab0-ffffffff81ffccdd: subflow_ulp_clone (STB_LOCAL)
ffffffff820b6804-ffffffff820b681f: subflow_ulp_clone.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void subflow_ulp_clone(const struct request_sock *req, struct sock *newsk, const gfp_t priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/subflow.c (0)
Location: net/mptcp/subflow.c:1935
Inline: False
```
**Symbols:**

```
ffffffff82078df0-ffffffff8207901d: subflow_ulp_clone (STB_LOCAL)
ffffffff82137b82-ffffffff82137b9d: subflow_ulp_clone.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void subflow_ulp_clone(const struct request_sock *req, struct sock *newsk, const gfp_t priority);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/subflow.c (0)
Location: net/mptcp/subflow.c:1932
Inline: False
```
**Symbols:**

```
ffffffff8214e050-ffffffff8214e27f: subflow_ulp_clone (STB_LOCAL)
ffffffff82219a50-ffffffff82219a6b: subflow_ulp_clone.cold (STB_LOCAL)
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
