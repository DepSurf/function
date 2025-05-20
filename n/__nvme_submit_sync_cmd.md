# Function: <code>__nvme_submit_sync_cmd</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int __nvme_submit_sync_cmd(struct request_queue *q, struct nvme_command *cmd, union nvme_result *result, void *buffer, unsigned int bufflen, unsigned int timeout, int qid, int at_head, blk_mq_req_flags_t flags, bool poll);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvme/host/core.c (ffffffff817439d0)
Location: drivers/nvme/host/core.c:817
Inline: False
Direct callers:
  - drivers/nvme/host/core.c:nvme_scan_work
  - drivers/nvme/host/core.c:nvme_get_log
  - drivers/nvme/host/core.c:nvme_sec_submit
  - drivers/nvme/host/core.c:nvme_pr_command
  - drivers/nvme/host/core.c:nvme_pr_command
  - drivers/nvme/host/core.c:nvme_report_ns_ids
  - drivers/nvme/host/core.c:nvme_features
  - drivers/nvme/host/core.c:nvme_toggle_streams
```
**Symbols:**

```
ffffffff817439d0-ffffffff81743baf: __nvme_submit_sync_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __nvme_submit_sync_cmd(struct request_queue *q, struct nvme_command *cmd, union nvme_result *result, void *buffer, unsigned int bufflen, unsigned int timeout, int qid, int at_head, blk_mq_req_flags_t flags, bool poll);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvme/host/core.c (ffffffff81725660)
Location: drivers/nvme/host/core.c:817
Inline: False
Direct callers:
  - drivers/nvme/host/core.c:nvme_scan_work
  - drivers/nvme/host/core.c:nvme_get_log
  - drivers/nvme/host/core.c:nvme_sec_submit
  - drivers/nvme/host/core.c:nvme_pr_command
  - drivers/nvme/host/core.c:nvme_pr_command
  - drivers/nvme/host/core.c:nvme_report_ns_ids
  - drivers/nvme/host/core.c:nvme_features
  - drivers/nvme/host/core.c:nvme_toggle_streams
```
**Symbols:**

```
ffffffff81725660-ffffffff8172583f: __nvme_submit_sync_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Flavor</b>
<ul>
</ul>
