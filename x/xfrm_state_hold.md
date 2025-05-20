# Function: <code>xfrm_state_hold</code>

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
In net/xfrm/xfrm_state.c (ffffffff817b6ca9)
Location: include/net/xfrm.h:817
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_state_flush
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
```
In net/xfrm/xfrm_input.c (ffffffff817bb831)
Location: include/net/xfrm.h:817
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:secpath_dup
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
In net/xfrm/xfrm_state.c (ffffffff818267b4)
Location: include/net/xfrm.h:813
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup_byaddr
  - net/xfrm/xfrm_state.c:__xfrm_state_lookup
  - net/xfrm/xfrm_state.c:xfrm_state_flush
```
```
In net/xfrm/xfrm_input.c (ffffffff8182874e)
Location: include/net/xfrm.h:813
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:secpath_dup
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
In net/xfrm/xfrm_state.c (ffffffff81857fc4)
Location: include/net/xfrm.h:813
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_state_flush
```
```
In net/xfrm/xfrm_input.c (ffffffff8185a12e)
Location: include/net/xfrm.h:813
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:secpath_dup
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
In net/xfrm/xfrm_state.c (ffffffff8187bd83)
Location: include/net/xfrm.h:850
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
```
```
In net/xfrm/xfrm_input.c (ffffffff8187df51)
Location: include/net/xfrm.h:850
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:secpath_dup
```
```
In net/xfrm/xfrm_output.c (ffffffff8187ef75)
Location: include/net/xfrm.h:850
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
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
In net/xfrm/xfrm_state.c (ffffffff818fcc93)
Location: include/net/xfrm.h:856
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
```
```
In net/xfrm/xfrm_input.c (ffffffff818fedf5)
Location: include/net/xfrm.h:856
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:secpath_dup
```
```
In net/xfrm/xfrm_output.c (ffffffff8190009a)
Location: include/net/xfrm.h:856
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
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
In net/xfrm/xfrm_state.c (ffffffff819533eb)
Location: include/net/xfrm.h:857
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
```
```
In net/xfrm/xfrm_input.c (ffffffff819558be)
Location: include/net/xfrm.h:857
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:secpath_dup
```
```
In net/xfrm/xfrm_output.c (ffffffff81956b1c)
Location: include/net/xfrm.h:857
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
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
In net/core/skbuff.c (ffffffff8189d262)
Location: include/net/xfrm.h:875
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81987e43)
Location: include/net/xfrm.h:875
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
```
```
In net/xfrm/xfrm_output.c (ffffffff8198b750)
Location: include/net/xfrm.h:875
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
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
In net/core/skbuff.c (ffffffff818e7ae8)
Location: include/net/xfrm.h:802
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
```
```
In net/xfrm/xfrm_state.c (ffffffff819f1c0e)
Location: include/net/xfrm.h:802
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
```
```
In net/xfrm/xfrm_output.c (ffffffff819f6c77)
Location: include/net/xfrm.h:802
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
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
In net/core/skbuff.c (ffffffff81919fb8)
Location: include/net/xfrm.h:802
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81a28ade)
Location: include/net/xfrm.h:802
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
```
```
In net/xfrm/xfrm_output.c (ffffffff81a2d8e7)
Location: include/net/xfrm.h:802
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
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
In net/core/skbuff.c (ffffffff819f437c)
Location: include/net/xfrm.h:800
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81b1b20b)
Location: include/net/xfrm.h:800
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
```
```
In net/xfrm/xfrm_output.c (ffffffff81b20366)
Location: include/net/xfrm.h:800
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
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
In net/core/skbuff.c (ffffffff819f439c)
Location: include/net/xfrm.h:803
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81b299db)
Location: include/net/xfrm.h:803
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2eca6)
Location: include/net/xfrm.h:803
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
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
In net/core/skbuff.c (ffffffff819da55c)
Location: include/net/xfrm.h:803
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81b17601)
Location: include/net/xfrm.h:803
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1ca64)
Location: include/net/xfrm.h:803
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
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
In net/core/skbuff.c (ffffffff81a8a579)
Location: include/net/xfrm.h:799
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81bdb9b1)
Location: include/net/xfrm.h:799
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
```
```
In net/xfrm/xfrm_output.c (ffffffff81be13d6)
Location: include/net/xfrm.h:799
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
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
In net/core/skbuff.c (ffffffff81bff9d9)
Location: include/net/xfrm.h:802
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81d72727)
Location: include/net/xfrm.h:802
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
```
```
In net/xfrm/xfrm_output.c (ffffffff81d7830b)
Location: include/net/xfrm.h:802
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
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
In net/core/skbuff.c (ffffffff81da4f27)
Location: include/net/xfrm.h:819
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_maybe_cow
```
```
In net/xfrm/xfrm_state.c (ffffffff81f3e414)
Location: include/net/xfrm.h:819
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
```
```
In net/xfrm/xfrm_output.c (ffffffff81f44b84)
Location: include/net/xfrm.h:819
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e13ae7)
Location: include/net/xfrm.h:824
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_maybe_cow
```
```
In net/xfrm/xfrm_state.c (ffffffff81f9dbcd)
Location: include/net/xfrm.h:824
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa43ba)
Location: include/net/xfrm.h:824
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ed0ca7)
Location: include/net/xfrm.h:824
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_maybe_cow
```
```
In net/xfrm/xfrm_state.c (ffffffff8206af2d)
Location: include/net/xfrm.h:824
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
```
```
In net/xfrm/xfrm_output.c (ffffffff82071731)
Location: include/net/xfrm.h:824
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
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
In net/core/skbuff.c (ffff800010bb27a8)
Location: include/net/xfrm.h:802
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
```
```
In net/xfrm/xfrm_state.c (ffff800010ce5a70)
Location: include/net/xfrm.h:802
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
```
```
In net/xfrm/xfrm_output.c (ffff800010cec684)
Location: include/net/xfrm.h:802
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
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
In net/core/skbuff.c (c0cd09f4)
Location: include/net/xfrm.h:802
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
```
```
In net/xfrm/xfrm_state.c (c0debde4)
Location: include/net/xfrm.h:802
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_find_acq_byseq
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
```
```
In net/xfrm/xfrm_output.c (c0df45ac)
Location: include/net/xfrm.h:802
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
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
In net/core/skbuff.c (c000000000c8a380)
Location: include/net/xfrm.h:802
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
```
```
In net/xfrm/xfrm_state.c (c000000000e043e4)
Location: include/net/xfrm.h:802
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_find_acq_byseq
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
```
```
In net/xfrm/xfrm_output.c (c000000000e1087c)
Location: include/net/xfrm.h:802
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
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
In net/core/skbuff.c (ffffffe00074461c)
Location: include/net/xfrm.h:802
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
```
```
In net/xfrm/xfrm_state.c (ffffffe0008305ec)
Location: include/net/xfrm.h:802
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_find_acq_byseq
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
```
```
In net/xfrm/xfrm_output.c (ffffffe000839d66)
Location: include/net/xfrm.h:802
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
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
In net/core/skbuff.c (ffffffff818b9fb8)
Location: include/net/xfrm.h:802
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
```
```
In net/xfrm/xfrm_state.c (ffffffff819c816e)
Location: include/net/xfrm.h:802
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
```
```
In net/xfrm/xfrm_output.c (ffffffff819ccf77)
Location: include/net/xfrm.h:802
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
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
In net/core/skbuff.c (ffffffff81873f08)
Location: include/net/xfrm.h:802
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81984f5e)
Location: include/net/xfrm.h:802
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
```
```
In net/xfrm/xfrm_output.c (ffffffff81989d67)
Location: include/net/xfrm.h:802
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
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
In net/core/skbuff.c (ffffffff8190afb8)
Location: include/net/xfrm.h:802
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81a32bee)
Location: include/net/xfrm.h:802
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
```
```
In net/xfrm/xfrm_output.c (ffffffff81a379f7)
Location: include/net/xfrm.h:802
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
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
In net/core/skbuff.c (ffffffff8192c0b8)
Location: include/net/xfrm.h:802
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_ext_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3e53e)
Location: include/net/xfrm.h:802
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:__find_acq_core
  - net/xfrm/xfrm_state.c:xfrm_state_lookup_byspi
  - net/xfrm/xfrm_state.c:xfrm_stateonly_find
  - net/xfrm/xfrm_state.c:xfrm_dev_state_flush
  - net/xfrm/xfrm_state.c:xfrm_state_flush
```
```
In net/xfrm/xfrm_output.c (ffffffff81a433b7)
Location: include/net/xfrm.h:802
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output
```
</details>
</li>
</ul>

## Differences
