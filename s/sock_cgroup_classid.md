# Function: <code>sock_cgroup_classid</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8176765a)
Location: include/linux/cgroup-defs.h:617
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff81776407)
Location: include/linux/cgroup-defs.h:617
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/filter.c (ffffffff8179cd05)
Location: include/linux/cgroup-defs.h:617
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/core/netclassid_cgroup.c (ffffffff817aa7de)
Location: include/linux/cgroup-defs.h:617
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_sock
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81794662)
Location: include/linux/cgroup-defs.h:621
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff817a3687)
Location: include/linux/cgroup-defs.h:621
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/filter.c (ffffffff817ca395)
Location: include/linux/cgroup-defs.h:621
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/core/netclassid_cgroup.c (ffffffff817d92fe)
Location: include/linux/cgroup-defs.h:621
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_sock
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817b48b3)
Location: include/linux/cgroup-defs.h:644
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff817c18aa)
Location: include/linux/cgroup-defs.h:644
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/filter.c (ffffffff817e9338)
Location: include/linux/cgroup-defs.h:644
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/core/netclassid_cgroup.c (ffffffff817f85ce)
Location: include/linux/cgroup-defs.h:644
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8182cb13)
Location: include/linux/cgroup-defs.h:764
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff8183b2b7)
Location: include/linux/cgroup-defs.h:764
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/filter.c (ffffffff81864738)
Location: include/linux/cgroup-defs.h:764
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/core/netclassid_cgroup.c (ffffffff81875e9e)
Location: include/linux/cgroup-defs.h:764
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81877646)
Location: include/linux/cgroup-defs.h:776
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff81885907)
Location: include/linux/cgroup-defs.h:776
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/filter.c (ffffffff818b1888)
Location: include/linux/cgroup-defs.h:776
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/core/netclassid_cgroup.c (ffffffff818c746e)
Location: include/linux/cgroup-defs.h:776
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_sock
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81897a96)
Location: include/linux/cgroup-defs.h:785
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff818a6037)
Location: include/linux/cgroup-defs.h:785
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/filter.c (ffffffff818d62b8)
Location: include/linux/cgroup-defs.h:785
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/core/netclassid_cgroup.c (ffffffff818f05ae)
Location: include/linux/cgroup-defs.h:785
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_sock
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818e1fb8)
Location: include/linux/cgroup-defs.h:828
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff818f14cc)
Location: include/linux/cgroup-defs.h:828
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/filter.c (ffffffff81923a88)
Location: include/linux/cgroup-defs.h:828
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/core/netclassid_cgroup.c (ffffffff81941f1e)
Location: include/linux/cgroup-defs.h:828
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_sock
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81914188)
Location: include/linux/cgroup-defs.h:828
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff8192341c)
Location: include/linux/cgroup-defs.h:828
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/filter.c (ffffffff81955cb8)
Location: include/linux/cgroup-defs.h:828
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/core/netclassid_cgroup.c (ffffffff81976e14)
Location: include/linux/cgroup-defs.h:828
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_sock
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e85a3)
Location: include/linux/cgroup-defs.h:825
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff819f6b48)
Location: include/linux/cgroup-defs.h:825
Inline: True
Inline callers:
  - net/core/scm.c:__scm_install_fd
```
```
In net/core/filter.c (ffffffff81a297e8)
Location: include/linux/cgroup-defs.h:825
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/core/netclassid_cgroup.c (ffffffff81a4bbc4)
Location: include/linux/cgroup-defs.h:825
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_sock
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e8223)
Location: include/linux/cgroup-defs.h:810
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:sk_alloc
```
```
In net/core/filter.c (ffffffff81a2a148)
Location: include/linux/cgroup-defs.h:810
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_cgroup_classid
  - net/core/filter.c:bpf_skb_cgroup_classid
```
```
In net/core/netclassid_cgroup.c (ffffffff81a517fd)
Location: include/linux/cgroup-defs.h:810
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_sock
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819ce355)
Location: include/linux/cgroup-defs.h:810
Inline: True
Inline callers:
  - net/core/sock.c:__receive_sock
  - net/core/sock.c:sk_alloc
```
```
In net/core/filter.c (ffffffff81a1139f)
Location: include/linux/cgroup-defs.h:810
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_cgroup_classid
  - net/core/filter.c:bpf_skb_cgroup_classid
```
```
In net/core/netclassid_cgroup.c (ffffffff81a37072)
Location: include/linux/cgroup-defs.h:810
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_sock
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
In net/core/filter.c (ffffffff81acc7ad)
Location: include/linux/cgroup-defs.h:780
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_cgroup_classid
  - net/core/filter.c:bpf_skb_cgroup_classid
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
In net/core/filter.c (ffffffff81c4963d)
Location: include/linux/cgroup-defs.h:781
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_cgroup_classid
  - net/core/filter.c:bpf_skb_cgroup_classid
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81dfe63d)
Location: include/linux/cgroup-defs.h:809
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_cgroup_classid
  - net/core/filter.c:bpf_skb_cgroup_classid
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e6f803)
Location: include/linux/cgroup-defs.h:809
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_cgroup_classid
  - net/core/filter.c:bpf_skb_cgroup_classid
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f2efd3)
Location: include/linux/cgroup-defs.h:845
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_cgroup_classid
  - net/core/filter.c:bpf_skb_cgroup_classid
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffff800010bab168)
Location: include/linux/cgroup-defs.h:828
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffff800010bbe620)
Location: include/linux/cgroup-defs.h:828
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/filter.c (ffff800010bf7a8c)
Location: include/linux/cgroup-defs.h:828
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/core/netclassid_cgroup.c (ffff800010c1d6d8)
Location: include/linux/cgroup-defs.h:828
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_sock
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c0cc9c20)
Location: include/linux/cgroup-defs.h:828
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (c0cda010)
Location: include/linux/cgroup-defs.h:828
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/filter.c (c0d112b0)
Location: include/linux/cgroup-defs.h:828
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/core/netclassid_cgroup.c (c0d35524)
Location: include/linux/cgroup-defs.h:828
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_sock
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c000000000c81964)
Location: include/linux/cgroup-defs.h:828
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (c000000000c97a14)
Location: include/linux/cgroup-defs.h:828
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/filter.c (c000000000cdda1c)
Location: include/linux/cgroup-defs.h:828
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/core/netclassid_cgroup.c (c000000000d0e8dc)
Location: include/linux/cgroup-defs.h:828
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_sock
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffe00073eb58)
Location: include/linux/cgroup-defs.h:828
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffe00074c594)
Location: include/linux/cgroup-defs.h:828
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/filter.c (ffffffe000779494)
Location: include/linux/cgroup-defs.h:828
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/core/netclassid_cgroup.c (ffffffe000797254)
Location: include/linux/cgroup-defs.h:828
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_sock
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818b4188)
Location: include/linux/cgroup-defs.h:828
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff818c341c)
Location: include/linux/cgroup-defs.h:828
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/filter.c (ffffffff818f5c88)
Location: include/linux/cgroup-defs.h:828
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/core/netclassid_cgroup.c (ffffffff81916c84)
Location: include/linux/cgroup-defs.h:828
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_sock
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8186e0d8)
Location: include/linux/cgroup-defs.h:828
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff8187d35c)
Location: include/linux/cgroup-defs.h:828
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/filter.c (ffffffff818afab8)
Location: include/linux/cgroup-defs.h:828
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/core/netclassid_cgroup.c (ffffffff818d0a34)
Location: include/linux/cgroup-defs.h:828
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_sock
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81905188)
Location: include/linux/cgroup-defs.h:828
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff8191441c)
Location: include/linux/cgroup-defs.h:828
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/filter.c (ffffffff81946cb8)
Location: include/linux/cgroup-defs.h:828
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/core/netclassid_cgroup.c (ffffffff81967e14)
Location: include/linux/cgroup-defs.h:828
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_sock
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81926247)
Location: include/linux/cgroup-defs.h:828
Inline: True
Inline callers:
  - net/core/sock.c:sk_alloc
```
```
In net/core/scm.c (ffffffff81935688)
Location: include/linux/cgroup-defs.h:828
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/core/filter.c (ffffffff819685c8)
Location: include/linux/cgroup-defs.h:828
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_cgroup_classid
```
```
In net/core/netclassid_cgroup.c (ffffffff8198a1d4)
Location: include/linux/cgroup-defs.h:828
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:update_classid_sock
```
</details>
</li>
</ul>

## Differences
