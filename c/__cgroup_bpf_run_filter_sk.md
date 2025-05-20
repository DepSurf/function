# Function: <code>__cgroup_bpf_run_filter_sk</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sk(struct sock *sk, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81197580)
Location: kernel/bpf/cgroup.c:217
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_create
```
**Symbols:**

```
ffffffff81197580-ffffffff811975cc: __cgroup_bpf_run_filter_sk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sk(struct sock *sk, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8119f1b0)
Location: kernel/bpf/cgroup.c:220
Inline: False
```
**Symbols:**

```
ffffffff8119f1b0-ffffffff8119f1fc: __cgroup_bpf_run_filter_sk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sk(struct sock *sk, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811b2160)
Location: kernel/bpf/cgroup.c:486
Inline: False
```
**Symbols:**

```
ffffffff811b2160-ffffffff811b21e2: __cgroup_bpf_run_filter_sk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sk(struct sock *sk, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811d16f0)
Location: kernel/bpf/cgroup.c:539
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv6/af_inet6.c:__inet6_bind
```
**Symbols:**

```
ffffffff811d16f0-ffffffff811d1772: __cgroup_bpf_run_filter_sk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sk(struct sock *sk, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811e1270)
Location: kernel/bpf/cgroup.c:596
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv6/af_inet6.c:__inet6_bind
```
**Symbols:**

```
ffffffff811e1270-ffffffff811e1314: __cgroup_bpf_run_filter_sk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sk(struct sock *sk, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811f7490)
Location: kernel/bpf/cgroup.c:669
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv6/af_inet6.c:__inet6_bind
```
**Symbols:**

```
ffffffff811f7490-ffffffff811f758c: __cgroup_bpf_run_filter_sk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sk(struct sock *sk, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81204430)
Location: kernel/bpf/cgroup.c:679
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv6/af_inet6.c:__inet6_bind
```
**Symbols:**

```
ffffffff81204430-ffffffff8120452c: __cgroup_bpf_run_filter_sk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sk(struct sock *sk, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8122c160)
Location: kernel/bpf/cgroup.c:1016
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv6/af_inet6.c:__inet6_bind
```
**Symbols:**

```
ffffffff8122c160-ffffffff8122c25f: __cgroup_bpf_run_filter_sk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sk(struct sock *sk, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81234550)
Location: kernel/bpf/cgroup.c:1040
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_release
  - net/ipv6/af_inet6.c:__inet6_bind
```
**Symbols:**

```
ffffffff81234550-ffffffff81234656: __cgroup_bpf_run_filter_sk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sk(struct sock *sk, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81239270)
Location: kernel/bpf/cgroup.c:1040
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_release
  - net/ipv6/af_inet6.c:__inet6_bind
```
**Symbols:**

```
ffffffff81239270-ffffffff8123940a: __cgroup_bpf_run_filter_sk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sk(struct sock *sk, enum cgroup_bpf_attach_type atype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81273360)
Location: kernel/bpf/cgroup.c:1070
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_release
  - net/ipv6/af_inet6.c:__inet6_bind
```
**Symbols:**

```
ffffffff81273360-ffffffff812734b1: __cgroup_bpf_run_filter_sk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sk(struct sock *sk, enum cgroup_bpf_attach_type atype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff812c2b30)
Location: kernel/bpf/cgroup.c:1223
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_release
  - net/ipv6/af_inet6.c:__inet6_bind
```
**Symbols:**

```
ffffffff812c2b30-ffffffff812c2c97: __cgroup_bpf_run_filter_sk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sk(struct sock *sk, enum cgroup_bpf_attach_type atype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81327450)
Location: kernel/bpf/cgroup.c:1437
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_release
  - net/ipv6/af_inet6.c:__inet6_bind
```
**Symbols:**

```
ffffffff81327450-ffffffff813275b7: __cgroup_bpf_run_filter_sk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sk(struct sock *sk, enum cgroup_bpf_attach_type atype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81357610)
Location: kernel/bpf/cgroup.c:1437
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_release
  - net/ipv6/af_inet6.c:__inet6_bind
```
**Symbols:**

```
ffffffff81357610-ffffffff81357777: __cgroup_bpf_run_filter_sk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sk(struct sock *sk, enum cgroup_bpf_attach_type atype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff813802c0)
Location: kernel/bpf/cgroup.c:1438
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv4/af_inet.c:inet_release
  - net/ipv6/af_inet6.c:__inet6_bind
```
**Symbols:**

```
ffffffff813802c0-ffffffff81380427: __cgroup_bpf_run_filter_sk (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sk(struct sock *sk, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffff80001028db90)
Location: kernel/bpf/cgroup.c:679
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv6/af_inet6.c:__inet6_bind
```
**Symbols:**

```
ffff80001028db90-ffff80001028dcdc: __cgroup_bpf_run_filter_sk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sk(struct sock *sk, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (c04bc318)
Location: kernel/bpf/cgroup.c:679
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv6/af_inet6.c:__inet6_bind
```
**Symbols:**

```
c04bc318-c04bc4e0: __cgroup_bpf_run_filter_sk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sk(struct sock *sk, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (c00000000033a210)
Location: kernel/bpf/cgroup.c:679
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv6/af_inet6.c:__inet6_bind
```
**Symbols:**

```
c00000000033a210-c00000000033a3f0: __cgroup_bpf_run_filter_sk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sk(struct sock *sk, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffe0001c05c4)
Location: kernel/bpf/cgroup.c:679
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv6/af_inet6.c:__inet6_bind
```
**Symbols:**

```
ffffffe0001c05c4-ffffffe0001c0718: __cgroup_bpf_run_filter_sk (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sk(struct sock *sk, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811fca50)
Location: kernel/bpf/cgroup.c:679
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv6/af_inet6.c:__inet6_bind
```
**Symbols:**

```
ffffffff811fca50-ffffffff811fcb4c: __cgroup_bpf_run_filter_sk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sk(struct sock *sk, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811ef7a0)
Location: kernel/bpf/cgroup.c:679
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv6/af_inet6.c:__inet6_bind
```
**Symbols:**

```
ffffffff811ef7a0-ffffffff811ef89c: __cgroup_bpf_run_filter_sk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sk(struct sock *sk, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811fa820)
Location: kernel/bpf/cgroup.c:679
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv6/af_inet6.c:__inet6_bind
```
**Symbols:**

```
ffffffff811fa820-ffffffff811fa91c: __cgroup_bpf_run_filter_sk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_sk(struct sock *sk, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81209460)
Location: kernel/bpf/cgroup.c:679
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:__inet_bind
  - net/ipv6/af_inet6.c:__inet6_bind
```
**Symbols:**

```
ffffffff81209460-ffffffff81209574: __cgroup_bpf_run_filter_sk (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Param added. </b>
<code>enum cgroup_bpf_attach_type atype</code>
</li>
<li>
<b>Param removed. </b>
<code>enum bpf_attach_type type</code>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
