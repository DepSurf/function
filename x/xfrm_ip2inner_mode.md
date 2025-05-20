# Function: <code>xfrm_ip2inner_mode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff817b25c6)
Location: include/net/xfrm.h:462
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
```
In net/xfrm/xfrm_input.c (ffffffff817bb620)
Location: include/net/xfrm.h:462
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff817bc07a)
Location: include/net/xfrm.h:462
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8181f5b2)
Location: include/net/xfrm.h:458
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
```
In net/xfrm/xfrm_input.c (ffffffff81828c6c)
Location: include/net/xfrm.h:458
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81828fba)
Location: include/net/xfrm.h:458
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
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
In net/xfrm/xfrm_policy.c (ffffffff81850e12)
Location: include/net/xfrm.h:458
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
```
In net/xfrm/xfrm_input.c (ffffffff8185a64c)
Location: include/net/xfrm.h:458
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
```
```
In net/xfrm/xfrm_output.c (ffffffff8185a99a)
Location: include/net/xfrm.h:458
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
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
In net/xfrm/xfrm_policy.c (ffffffff81875d62)
Location: include/net/xfrm.h:493
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
```
In net/xfrm/xfrm_input.c (ffffffff8187e6b4)
Location: include/net/xfrm.h:493
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
```
```
In net/xfrm/xfrm_output.c (ffffffff8187e92a)
Location: include/net/xfrm.h:493
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
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
In net/xfrm/xfrm_policy.c (ffffffff818f6e62)
Location: include/net/xfrm.h:500
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
```
In net/xfrm/xfrm_input.c (ffffffff818ff785)
Location: include/net/xfrm.h:500
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
```
```
In net/xfrm/xfrm_output.c (ffffffff818ff98a)
Location: include/net/xfrm.h:500
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
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
In net/xfrm/xfrm_policy.c (ffffffff8194cec9)
Location: include/net/xfrm.h:501
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
```
In net/xfrm/xfrm_input.c (ffffffff81956060)
Location: include/net/xfrm.h:501
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
```
```
In net/xfrm/xfrm_output.c (ffffffff8195640a)
Location: include/net/xfrm.h:501
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
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
In net/xfrm/xfrm_policy.c (ffffffff8197e78d)
Location: include/net/xfrm.h:509
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_input.c (ffffffff8198ac5c)
Location: include/net/xfrm.h:509
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
```
```
In net/xfrm/xfrm_output.c (ffffffff8198b08a)
Location: include/net/xfrm.h:509
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
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
In net/xfrm/xfrm_policy.c (ffffffff819e7793)
Location: include/net/xfrm.h:436
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_input.c (ffffffff819f5712)
Location: include/net/xfrm.h:436
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff819f5c92)
Location: include/net/xfrm.h:436
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
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
In net/xfrm/xfrm_policy.c (ffffffff81a1e783)
Location: include/net/xfrm.h:436
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2c3c2)
Location: include/net/xfrm.h:436
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a2c912)
Location: include/net/xfrm.h:436
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
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
In net/xfrm/xfrm_policy.c (ffffffff81b112eb)
Location: include/net/xfrm.h:432
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1e83c)
Location: include/net/xfrm.h:432
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1fae3)
Location: include/net/xfrm.h:432
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
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
In net/xfrm/xfrm_policy.c (ffffffff81b1fb8c)
Location: include/net/xfrm.h:435
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2d23f)
Location: include/net/xfrm.h:435
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2e3f3)
Location: include/net/xfrm.h:435
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
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
In net/xfrm/xfrm_policy.c (ffffffff81b0da6e)
Location: include/net/xfrm.h:435
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1ae82)
Location: include/net/xfrm.h:435
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1be63)
Location: include/net/xfrm.h:435
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81bd0638)
Location: include/net/xfrm.h:431
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_input.c (ffffffff81bdf3ec)
Location: include/net/xfrm.h:431
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81be0613)
Location: include/net/xfrm.h:431
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81d66ae2)
Location: include/net/xfrm.h:436
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_input.c (ffffffff81d76140)
Location: include/net/xfrm.h:436
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81d77652)
Location: include/net/xfrm.h:436
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81f3183b)
Location: include/net/xfrm.h:451
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_input.c (ffffffff81f4288c)
Location: include/net/xfrm.h:451
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81f43ef6)
Location: include/net/xfrm.h:451
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
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
In net/xfrm/xfrm_policy.c (ffffffff81f90ee5)
Location: include/net/xfrm.h:456
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
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
In net/xfrm/xfrm_policy.c (ffffffff8205ec5d)
Location: include/net/xfrm.h:456
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
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
In net/xfrm/xfrm_policy.c (ffff800010cdabfc)
Location: include/net/xfrm.h:436
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_input.c (ffff800010ceacac)
Location: include/net/xfrm.h:436
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffff800010ceb5ac)
Location: include/net/xfrm.h:436
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
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
In net/xfrm/xfrm_policy.c (c0de4a74)
Location: include/net/xfrm.h:436
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_input.c (c0df2fd0)
Location: include/net/xfrm.h:436
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
```
```
In net/xfrm/xfrm_output.c (c0df3464)
Location: include/net/xfrm.h:436
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
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
In net/xfrm/xfrm_policy.c (c000000000dffb54)
Location: include/net/xfrm.h:436
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_input.c (c000000000e0e9c0)
Location: include/net/xfrm.h:436
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (c000000000e0f380)
Location: include/net/xfrm.h:436
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
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
In net/xfrm/xfrm_policy.c (ffffffe00082c7b2)
Location: include/net/xfrm.h:436
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_input.c (ffffffe000838a08)
Location: include/net/xfrm.h:436
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffe000838f5e)
Location: include/net/xfrm.h:436
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
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
In net/xfrm/xfrm_policy.c (ffffffff819bde13)
Location: include/net/xfrm.h:436
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_input.c (ffffffff819cba52)
Location: include/net/xfrm.h:436
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff819cbfa2)
Location: include/net/xfrm.h:436
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
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
In net/xfrm/xfrm_policy.c (ffffffff8197ac03)
Location: include/net/xfrm.h:436
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_input.c (ffffffff81988842)
Location: include/net/xfrm.h:436
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81988d92)
Location: include/net/xfrm.h:436
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
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
In net/xfrm/xfrm_policy.c (ffffffff81a28893)
Location: include/net/xfrm.h:436
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_input.c (ffffffff81a364d2)
Location: include/net/xfrm.h:436
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a36a22)
Location: include/net/xfrm.h:436
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
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
In net/xfrm/xfrm_policy.c (ffffffff81a33e8f)
Location: include/net/xfrm.h:436
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_input.c (ffffffff81a41e1d)
Location: include/net/xfrm.h:436
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
```
In net/xfrm/xfrm_output.c (ffffffff81a42393)
Location: include/net/xfrm.h:436
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
```
</details>
</li>
</ul>

## Differences
