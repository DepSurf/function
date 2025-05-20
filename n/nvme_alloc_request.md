# Function: <code>nvme_alloc_request</code>

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
struct request *nvme_alloc_request(struct request_queue *q, struct nvme_command *cmd, blk_mq_req_flags_t flags, int qid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvme/host/core.c (ffffffff81741930)
Location: drivers/nvme/host/core.c:478
Inline: False
Direct callers:
  - drivers/nvme/host/core.c:nvme_submit_user_cmd
  - drivers/nvme/host/core.c:__nvme_submit_sync_cmd
  - drivers/nvme/host/lightnvm.c:nvme_nvm_submit_io
  - drivers/nvme/host/pci.c:__nvme_disable_io_queues
  - drivers/nvme/host/pci.c:nvme_timeout
```
**Symbols:**

```
ffffffff81741930-ffffffff817419a8: nvme_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct request *nvme_alloc_request(struct request_queue *q, struct nvme_command *cmd, blk_mq_req_flags_t flags, int qid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvme/host/core.c (ffffffff817235c0)
Location: drivers/nvme/host/core.c:478
Inline: False
Direct callers:
  - drivers/nvme/host/core.c:nvme_submit_user_cmd
  - drivers/nvme/host/core.c:__nvme_submit_sync_cmd
  - drivers/nvme/host/pci.c:__nvme_disable_io_queues
  - drivers/nvme/host/pci.c:nvme_timeout
```
**Symbols:**

```
ffffffff817235c0-ffffffff81723638: nvme_alloc_request (STB_GLOBAL)
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
