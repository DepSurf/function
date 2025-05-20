# Function: <code>vmbus_post_msg</code>

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
In <code>aws</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int vmbus_post_msg(void *buffer, size_t buflen, bool can_sleep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hv/connection.c (0)
Location: drivers/hv/connection.c:393
Inline: False
Direct callers:
  - drivers/hv/connection.c:vmbus_negotiate_version
  - drivers/hv/channel.c:vmbus_close_internal
  - drivers/hv/channel.c:vmbus_teardown_gpadl
  - drivers/hv/channel.c:vmbus_establish_gpadl
  - drivers/hv/channel.c:vmbus_establish_gpadl
  - drivers/hv/channel.c:vmbus_send_tl_connect_request
  - drivers/hv/channel.c:__vmbus_open
  - drivers/hv/channel_mgmt.c:vmbus_request_offers
  - drivers/hv/channel_mgmt.c:vmbus_initiate_unload
  - drivers/hv/channel_mgmt.c:vmbus_release_relid
```
**Symbols:**

```
ffffffff818506f0-ffffffff8185070a: vmbus_post_msg.cold (STB_LOCAL)
ffffffff81850040-ffffffff8185016e: vmbus_post_msg (STB_GLOBAL)
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
