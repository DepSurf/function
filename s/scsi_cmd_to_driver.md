# Function: <code>scsi_cmd_to_driver</code>

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
In drivers/scsi/scsi.c (ffffffff815a7b1e)
Location: include/scsi/scsi_cmnd.h:153
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff815aaae6)
Location: include/scsi/scsi_cmnd.h:153
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
```
In drivers/scsi/scsi_lib.c (ffffffff815ad11a)
Location: include/scsi/scsi_cmnd.h:153
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_unprep_fn
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
  - drivers/scsi/scsi_lib.c:scsi_setup_cmnd
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
In drivers/scsi/scsi.c (ffffffff815ff90e)
Location: include/scsi/scsi_cmnd.h:153
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff81602a6b)
Location: include/scsi/scsi_cmnd.h:153
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
```
In drivers/scsi/scsi_lib.c (ffffffff8160505b)
Location: include/scsi/scsi_cmnd.h:153
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_unprep_fn
  - drivers/scsi/scsi_lib.c:scsi_setup_cmnd
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
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
In drivers/scsi/scsi.c (ffffffff8162ef6e)
Location: include/scsi/scsi_cmnd.h:153
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff8163215b)
Location: include/scsi/scsi_cmnd.h:153
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
```
```
In drivers/scsi/scsi_lib.c (ffffffff8163473b)
Location: include/scsi/scsi_cmnd.h:153
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_unprep_fn
  - drivers/scsi/scsi_lib.c:scsi_setup_cmnd
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
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
In drivers/scsi/scsi.c (ffffffff81643d5f)
Location: include/scsi/scsi_cmnd.h:157
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff816459aa)
Location: include/scsi/scsi_cmnd.h:157
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_action
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff8164b29d)
Location: include/scsi/scsi_cmnd.h:157
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_setup_cmnd
  - drivers/scsi/scsi_lib.c:scsi_uninit_cmd
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
In drivers/scsi/scsi.c (ffffffff816ace6f)
Location: include/scsi/scsi_cmnd.h:164
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff816ae97a)
Location: include/scsi/scsi_cmnd.h:164
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_action
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff816b45da)
Location: include/scsi/scsi_cmnd.h:164
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_setup_cmnd
  - drivers/scsi/scsi_lib.c:scsi_uninit_cmd
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
In drivers/scsi/scsi.c (ffffffff816e938f)
Location: include/scsi/scsi_cmnd.h:163
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff816ead2a)
Location: include/scsi/scsi_cmnd.h:163
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_action
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff816f071a)
Location: include/scsi/scsi_cmnd.h:163
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_setup_cmnd
  - drivers/scsi/scsi_lib.c:scsi_uninit_cmd
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
In drivers/scsi/scsi.c (ffffffff8170ce8f)
Location: include/scsi/scsi_cmnd.h:166
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff8170e7da)
Location: include/scsi/scsi_cmnd.h:166
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_action
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff81715301)
Location: include/scsi/scsi_cmnd.h:166
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
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
In drivers/scsi/scsi.c (ffffffff8174856f)
Location: include/scsi/scsi_cmnd.h:155
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff81749f7a)
Location: include/scsi/scsi_cmnd.h:155
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_action
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff81750aab)
Location: include/scsi/scsi_cmnd.h:155
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
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
In drivers/scsi/scsi.c (ffffffff8176c6bf)
Location: include/scsi/scsi_cmnd.h:156
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff8176e0da)
Location: include/scsi/scsi_cmnd.h:156
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_action
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff81774cea)
Location: include/scsi/scsi_cmnd.h:156
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
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
In drivers/scsi/scsi.c (ffffffff8182e9c2)
Location: include/scsi/scsi_cmnd.h:157
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff8183069a)
Location: include/scsi/scsi_cmnd.h:157
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_action
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff81837c60)
Location: include/scsi/scsi_cmnd.h:157
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_prep_fn
  - drivers/scsi/scsi_lib.c:scsi_uninit_cmd
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
In drivers/scsi/scsi.c (ffffffff8183fa02)
Location: include/scsi/scsi_cmnd.h:157
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff8184130a)
Location: include/scsi/scsi_cmnd.h:157
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_action
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff81848640)
Location: include/scsi/scsi_cmnd.h:157
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_prepare_cmd
  - drivers/scsi/scsi_lib.c:scsi_uninit_cmd
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
In drivers/scsi/scsi.c (ffffffff81822c62)
Location: include/scsi/scsi_cmnd.h:159
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff818244fa)
Location: include/scsi/scsi_cmnd.h:159
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_action
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff8182b96a)
Location: include/scsi/scsi_cmnd.h:159
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_prepare_cmd
  - drivers/scsi/scsi_lib.c:scsi_uninit_cmd
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
In drivers/scsi/scsi.c (ffffffff818ad581)
Location: include/scsi/scsi_cmnd.h:161
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff818b163e)
Location: include/scsi/scsi_cmnd.h:161
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b795f)
Location: include/scsi/scsi_cmnd.h:161
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_prepare_cmd
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:scsi_end_request
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
In drivers/scsi/scsi.c (ffffffff819f8282)
Location: include/scsi/scsi_driver.h:34
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff819fc6bb)
Location: include/scsi/scsi_driver.h:34
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff81a02ed3)
Location: include/scsi/scsi_driver.h:34
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_prepare_cmd
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:scsi_end_request
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
In drivers/scsi/scsi.c (ffffffff81b75c52)
Location: include/scsi/scsi_driver.h:34
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff81b7a87b)
Location: include/scsi/scsi_driver.h:34
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b81a25)
Location: include/scsi/scsi_driver.h:34
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_prepare_cmd
  - drivers/scsi/scsi_lib.c:scsi_io_completion
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:scsi_io_completion_action
  - drivers/scsi/scsi_lib.c:scsi_end_request
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
In drivers/scsi/scsi.c (ffffffff81bc9572)
Location: include/scsi/scsi_driver.h:34
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff81bce58b)
Location: include/scsi/scsi_driver.h:34
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd576a)
Location: include/scsi/scsi_driver.h:34
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_prepare_cmd
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
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
In drivers/scsi/scsi.c (ffffffff81c1e162)
Location: include/scsi/scsi_driver.h:34
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff81c231ab)
Location: include/scsi/scsi_driver.h:34
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c2a3be)
Location: include/scsi/scsi_driver.h:34
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_prepare_cmd
  - drivers/scsi/scsi_lib.c:scsi_end_request
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
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
In drivers/scsi/scsi.c (ffff80001096ecb8)
Location: include/scsi/scsi_cmnd.h:156
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffff800010971028)
Location: include/scsi/scsi_cmnd.h:156
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_action
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffff800010979078)
Location: include/scsi/scsi_cmnd.h:156
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
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
In drivers/scsi/scsi.c (c0a44134)
Location: include/scsi/scsi_cmnd.h:156
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (c0a45c74)
Location: include/scsi/scsi_cmnd.h:156
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_action
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (c0a4cd5c)
Location: include/scsi/scsi_cmnd.h:156
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
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
In drivers/scsi/scsi.c (c000000000a280a4)
Location: include/scsi/scsi_cmnd.h:156
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (c000000000a2a478)
Location: include/scsi/scsi_cmnd.h:156
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_action
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (c000000000a33518)
Location: include/scsi/scsi_cmnd.h:156
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
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
In drivers/scsi/scsi.c (ffffffe0005d8e72)
Location: include/scsi/scsi_cmnd.h:156
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffe0005da646)
Location: include/scsi/scsi_cmnd.h:156
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_action
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffffffe0005e05e8)
Location: include/scsi/scsi_cmnd.h:156
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
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
In drivers/scsi/scsi.c (ffffffff81720daf)
Location: include/scsi/scsi_cmnd.h:156
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff817227ca)
Location: include/scsi/scsi_cmnd.h:156
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_action
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff817293da)
Location: include/scsi/scsi_cmnd.h:156
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
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
In drivers/scsi/scsi.c (ffffffff816fa1df)
Location: include/scsi/scsi_cmnd.h:156
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff816fbbfa)
Location: include/scsi/scsi_cmnd.h:156
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_action
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff81702804)
Location: include/scsi/scsi_cmnd.h:156
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
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
In drivers/scsi/scsi.c (ffffffff8175fb7f)
Location: include/scsi/scsi_cmnd.h:156
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff8176159a)
Location: include/scsi/scsi_cmnd.h:156
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_action
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff817681aa)
Location: include/scsi/scsi_cmnd.h:156
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
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
In drivers/scsi/scsi.c (ffffffff8177b1df)
Location: include/scsi/scsi_cmnd.h:156
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/scsi_error.c (ffffffff8177cbfa)
Location: include/scsi/scsi_cmnd.h:156
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_action
  - drivers/scsi/scsi_error.c:scsi_eh_scmd_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff817838ea)
Location: include/scsi/scsi_cmnd.h:156
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_uninit_cmd
```
</details>
</li>
</ul>

## Differences
