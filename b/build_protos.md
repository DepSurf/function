# Function: <code>build_protos</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/sockmap.c (ffffffff811cc8f5)
Location: kernel/bpf/sockmap.c:183
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:bpf_tcp_ulp_register
  - kernel/bpf/sockmap.c:bpf_tcp_init
```
</details>
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
void build_protos(struct proto *espintcp_prot, struct proto_ops *espintcp_ops, const struct proto *orig_prot, const struct proto_ops *orig_ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/espintcp.c (ffffffff81b22c60)
Location: net/xfrm/espintcp.c:552
Inline: False
Direct callers:
  - net/xfrm/espintcp.c:espintcp_init_sk
  - net/xfrm/espintcp.c:espintcp_init
```
**Symbols:**

```
ffffffff81b22c60-ffffffff81b22cba: build_protos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void build_protos(struct proto *espintcp_prot, struct proto_ops *espintcp_ops, const struct proto *orig_prot, const struct proto_ops *orig_ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/espintcp.c (ffffffff81b313e0)
Location: net/xfrm/espintcp.c:556
Inline: False
Direct callers:
  - net/xfrm/espintcp.c:espintcp_init_sk
  - net/xfrm/espintcp.c:espintcp_init
```
**Symbols:**

```
ffffffff81b313e0-ffffffff81b31437: build_protos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void build_protos(struct proto *espintcp_prot, struct proto_ops *espintcp_ops, const struct proto *orig_prot, const struct proto_ops *orig_ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/espintcp.c (ffffffff81b1f110)
Location: net/xfrm/espintcp.c:556
Inline: False
Direct callers:
  - net/xfrm/espintcp.c:espintcp_init_sk
  - net/xfrm/espintcp.c:espintcp_init
```
**Symbols:**

```
ffffffff81b1f110-ffffffff81b1f167: build_protos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void build_protos(struct proto *espintcp_prot, struct proto_ops *espintcp_ops, const struct proto *orig_prot, const struct proto_ops *orig_ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/espintcp.c (ffffffff81be3c50)
Location: net/xfrm/espintcp.c:556
Inline: False
Direct callers:
  - net/xfrm/espintcp.c:espintcp_init_sk
  - net/xfrm/espintcp.c:espintcp_init
```
**Symbols:**

```
ffffffff81be3c50-ffffffff81be3ca7: build_protos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void build_protos(struct proto *espintcp_prot, struct proto_ops *espintcp_ops, const struct proto *orig_prot, const struct proto_ops *orig_ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/espintcp.c (ffffffff81d7af90)
Location: net/xfrm/espintcp.c:554
Inline: False
Direct callers:
  - net/xfrm/espintcp.c:espintcp_init_sk
  - net/xfrm/espintcp.c:espintcp_init
```
**Symbols:**

```
ffffffff81d7af90-ffffffff81d7affb: build_protos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void build_protos(struct proto *espintcp_prot, struct proto_ops *espintcp_ops, const struct proto *orig_prot, const struct proto_ops *orig_ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/espintcp.c (ffffffff81f48210)
Location: net/xfrm/espintcp.c:555
Inline: False
Direct callers:
  - net/xfrm/espintcp.c:espintcp_init_sk
  - net/xfrm/espintcp.c:espintcp_init
```
**Symbols:**

```
ffffffff81f48210-ffffffff81f4827b: build_protos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void build_protos(struct proto *espintcp_prot, struct proto_ops *espintcp_ops, const struct proto *orig_prot, const struct proto_ops *orig_ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/espintcp.c (ffffffff81fa7d10)
Location: net/xfrm/espintcp.c:564
Inline: False
Direct callers:
  - net/xfrm/espintcp.c:espintcp_init_sk
  - net/xfrm/espintcp.c:espintcp_init
```
**Symbols:**

```
ffffffff81fa7d10-ffffffff81fa7d7b: build_protos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void build_protos(struct proto *espintcp_prot, struct proto_ops *espintcp_ops, const struct proto *orig_prot, const struct proto_ops *orig_ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/espintcp.c (ffffffff82074fd0)
Location: net/xfrm/espintcp.c:564
Inline: False
Direct callers:
  - net/xfrm/espintcp.c:espintcp_init_sk
  - net/xfrm/espintcp.c:espintcp_init
```
**Symbols:**

```
ffffffff82074fd0-ffffffff8207503b: build_protos (STB_LOCAL)
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
