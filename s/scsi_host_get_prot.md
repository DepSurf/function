# Function: <code>scsi_host_get_prot</code>

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
In drivers/scsi/scsi.c (0)
Location: include/scsi/scsi_host.h:866
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/scsi/scsi_host.h:866
Inline: True
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
In drivers/scsi/scsi.c (0)
Location: include/scsi/scsi_host.h:861
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/scsi/scsi_host.h:861
Inline: True
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
In drivers/scsi/scsi.c (0)
Location: include/scsi/scsi_host.h:869
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/scsi/scsi_host.h:869
Inline: True
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
In drivers/scsi/scsi_lib.c (0)
Location: include/scsi/scsi_host.h:859
Inline: True
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
In drivers/scsi/scsi_lib.c (0)
Location: include/scsi/scsi_host.h:854
Inline: True
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
In drivers/scsi/scsi_lib.c (0)
Location: include/scsi/scsi_host.h:830
Inline: True
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
In drivers/scsi/scsi_lib.c (0)
Location: include/scsi/scsi_host.h:809
Inline: True
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
In drivers/scsi/scsi_lib.c (0)
Location: include/scsi/scsi_host.h:802
Inline: True
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
In drivers/scsi/scsi_lib.c (0)
Location: include/scsi/scsi_host.h:814
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff818383b6)
Location: include/scsi/scsi_host.h:815
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_setup_tags
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - drivers/scsi/scsi_lib.c:scsi_mq_prep_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81848ce6)
Location: include/scsi/scsi_host.h:822
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_setup_tags
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - drivers/scsi/scsi_lib.c:scsi_prepare_cmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff8182c110)
Location: include/scsi/scsi_host.h:838
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_setup_tags
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - drivers/scsi/scsi_lib.c:scsi_prepare_cmd
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
In drivers/scsi/scsi_lib.c (ffffffff818b7cb0)
Location: include/scsi/scsi_host.h:839
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_setup_tags
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - drivers/scsi/scsi_lib.c:scsi_prepare_cmd
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
In drivers/scsi/scsi_lib.c (ffffffff81a03331)
Location: include/scsi/scsi_host.h:821
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_setup_tags
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - drivers/scsi/scsi_lib.c:scsi_prepare_cmd
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
In drivers/scsi/scsi_lib.c (ffffffff81b81da1)
Location: include/scsi/scsi_host.h:830
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_setup_tags
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - drivers/scsi/scsi_lib.c:scsi_prepare_cmd
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
In drivers/scsi/scsi_lib.c (ffffffff81bd5aa1)
Location: include/scsi/scsi_host.h:836
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_setup_tags
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - drivers/scsi/scsi_lib.c:scsi_prepare_cmd
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
In drivers/scsi/scsi_lib.c (ffffffff81c2a6f1)
Location: include/scsi/scsi_host.h:839
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_setup_tags
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - drivers/scsi/scsi_lib.c:scsi_prepare_cmd
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
In drivers/scsi/scsi_lib.c (0)
Location: include/scsi/scsi_host.h:814
Inline: True
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
In drivers/scsi/scsi_lib.c (c0a4d450)
Location: include/scsi/scsi_host.h:814
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_setup_tags
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
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
In drivers/scsi/scsi_lib.c (c000000000a33fb0)
Location: include/scsi/scsi_host.h:814
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_setup_tags
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
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
In drivers/scsi/scsi_lib.c (ffffffe0005e0d9c)
Location: include/scsi/scsi_host.h:814
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_setup_tags
  - drivers/scsi/scsi_lib.c:scsi_mq_init_request
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
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
In drivers/scsi/scsi_lib.c (0)
Location: include/scsi/scsi_host.h:814
Inline: True
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
In drivers/scsi/scsi_lib.c (0)
Location: include/scsi/scsi_host.h:814
Inline: True
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
In drivers/scsi/scsi_lib.c (0)
Location: include/scsi/scsi_host.h:814
Inline: True
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
In drivers/scsi/scsi_lib.c (0)
Location: include/scsi/scsi_host.h:814
Inline: True
```
</details>
</li>
</ul>

## Differences
