# Function: <code>hystart_update</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff817aca8a)
Location: net/ipv4/tcp_cubic.c:389
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff818199ee)
Location: net/ipv4/tcp_cubic.c:389
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff8184b2ae)
Location: net/ipv4/tcp_cubic.c:389
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff8186ed2e)
Location: net/ipv4/tcp_cubic.c:389
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff818ef6be)
Location: net/ipv4/tcp_cubic.c:378
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff8194601e)
Location: net/ipv4/tcp_cubic.c:378
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff819761be)
Location: net/ipv4/tcp_cubic.c:378
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff819dfd43)
Location: net/ipv4/tcp_cubic.c:379
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff81a16d33)
Location: net/ipv4/tcp_cubic.c:379
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void hystart_update(struct sock *sk, u32 delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff81b07d90)
Location: net/ipv4/tcp_cubic.c:395
Inline: False
Direct callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
```
**Symbols:**

```
ffffffff81b07d90-ffffffff81b07f6f: hystart_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void hystart_update(struct sock *sk, u32 delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff81b16170)
Location: net/ipv4/tcp_cubic.c:395
Inline: False
Direct callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
```
**Symbols:**

```
ffffffff81b16170-ffffffff81b1634f: hystart_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void hystart_update(struct sock *sk, u32 delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff81b03f50)
Location: net/ipv4/tcp_cubic.c:386
Inline: False
Direct callers:
  - net/ipv4/tcp_cubic.c:cubictcp_acked
```
**Symbols:**

```
ffffffff81b03f50-ffffffff81b04123: hystart_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void hystart_update(struct sock *sk, u32 delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff81bc6260)
Location: net/ipv4/tcp_cubic.c:384
Inline: False
Direct callers:
  - net/ipv4/tcp_cubic.c:cubictcp_acked
```
**Symbols:**

```
ffffffff81bc6260-ffffffff81bc646e: hystart_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void hystart_update(struct sock *sk, u32 delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff81d5b570)
Location: net/ipv4/tcp_cubic.c:386
Inline: False
Direct callers:
  - net/ipv4/tcp_cubic.c:cubictcp_acked
```
**Symbols:**

```
ffffffff81d5b570-ffffffff81d5b7a9: hystart_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void hystart_update(struct sock *sk, u32 delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff81f25a20)
Location: net/ipv4/tcp_cubic.c:386
Inline: False
Direct callers:
  - net/ipv4/tcp_cubic.c:cubictcp_acked
```
**Symbols:**

```
ffffffff81f25a20-ffffffff81f25c59: hystart_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void hystart_update(struct sock *sk, u32 delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff81f85a00)
Location: net/ipv4/tcp_cubic.c:386
Inline: False
Direct callers:
  - net/ipv4/tcp_cubic.c:cubictcp_acked
```
**Symbols:**

```
ffffffff81f85a00-ffffffff81f85c41: hystart_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void hystart_update(struct sock *sk, u32 delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff8204c0d0)
Location: net/ipv4/tcp_cubic.c:386
Inline: False
Direct callers:
  - net/ipv4/tcp_cubic.c:cubictcp_acked
```
**Symbols:**

```
ffffffff8204c0d0-ffffffff8204c311: hystart_update (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffff800010cd2eb4)
Location: net/ipv4/tcp_cubic.c:379
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (c0ddca40)
Location: net/ipv4/tcp_cubic.c:379
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (c000000000df1060)
Location: net/ipv4/tcp_cubic.c:379
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffe000823c5a)
Location: net/ipv4/tcp_cubic.c:379
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff819b63c3)
Location: net/ipv4/tcp_cubic.c:379
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff819731b3)
Location: net/ipv4/tcp_cubic.c:379
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff81a20e43)
Location: net/ipv4/tcp_cubic.c:379
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_cubic.c (ffffffff81a2c1a3)
Location: net/ipv4/tcp_cubic.c:379
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_acked
```
</details>
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
