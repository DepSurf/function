# Function: <code>skwq_has_sleeper</code>

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
In net/core/sock.c (ffffffff81767a6c)
Location: include/net/sock.h:1887
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff81775a11)
Location: include/net/sock.h:1887
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff8182b79d)
Location: include/net/sock.h:1887
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
In net/core/sock.c (ffffffff81794a8c)
Location: include/net/sock.h:1949
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff817a2fe1)
Location: include/net/sock.h:1949
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff8185d1bd)
Location: include/net/sock.h:1949
Inline: True
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
In net/core/sock.c (ffffffff817b2c7c)
Location: include/net/sock.h:1973
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff817c112d)
Location: include/net/sock.h:1973
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff818819df)
Location: include/net/sock.h:1973
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
In kernel/bpf/sockmap.c (ffffffff811b1718)
Location: include/net/sock.h:1987
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:smap_state_change
```
```
In net/core/sock.c (ffffffff8182af6c)
Location: include/net/sock.h:1987
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff8183ab50)
Location: include/net/sock.h:1987
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff81902b1f)
Location: include/net/sock.h:1987
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
In net/core/sock.c (ffffffff8187505c)
Location: include/net/sock.h:1989
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff8188528f)
Location: include/net/sock.h:1989
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff81958f9d)
Location: include/net/sock.h:1989
Inline: True
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
In net/core/sock.c (ffffffff8189592c)
Location: include/net/sock.h:2074
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff818a59c4)
Location: include/net/sock.h:2074
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff8198db5d)
Location: include/net/sock.h:2074
Inline: True
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
In net/core/sock.c (ffffffff818e0bf6)
Location: include/net/sock.h:2086
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff818f0cd4)
Location: include/net/sock.h:2086
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff819f90fd)
Location: include/net/sock.h:2086
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_write_space
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
In net/core/sock.c (ffffffff81912dc6)
Location: include/net/sock.h:2096
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff81922c49)
Location: include/net/sock.h:2096
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff81a2fd4d)
Location: include/net/sock.h:2096
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_write_space
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
In net/core/sock.c (ffffffff819e4b96)
Location: include/net/sock.h:2145
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff819f66c5)
Location: include/net/sock.h:2145
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff81b23f2d)
Location: include/net/sock.h:2145
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_write_space
```
```
In net/mptcp/subflow.c (ffffffff81baf907)
Location: include/net/sock.h:2145
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_state_change
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
In net/core/sock.c (ffffffff819e4406)
Location: include/net/sock.h:2164
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff819f62a6)
Location: include/net/sock.h:2164
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff81b3291d)
Location: include/net/sock.h:2164
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_write_space
```
```
In net/mptcp/subflow.c (ffffffff81bc30ba)
Location: include/net/sock.h:2164
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_state_change
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
In net/core/sock.c (ffffffff819ca496)
Location: include/net/sock.h:2181
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff819dc432)
Location: include/net/sock.h:2181
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff81b2045d)
Location: include/net/sock.h:2181
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_write_space
```
```
In net/mptcp/subflow.c (ffffffff81bb37c6)
Location: include/net/sock.h:2181
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_state_change
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
In net/core/sock.c (ffffffff81a79a36)
Location: include/net/sock.h:2221
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff81a8c672)
Location: include/net/sock.h:2221
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff81be535d)
Location: include/net/sock.h:2221
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_write_space
```
```
In net/mptcp/subflow.c (ffffffff81c81efa)
Location: include/net/sock.h:2221
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_state_change
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
In net/core/sock.c (ffffffff81beddcb)
Location: include/net/sock.h:2339
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff81c01ef5)
Location: include/net/sock.h:2339
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff81d7d0e2)
Location: include/net/sock.h:2339
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_write_space
```
```
In net/mptcp/subflow.c (ffffffff81e27c0f)
Location: include/net/sock.h:2339
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_state_change
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
In net/core/sock.c (ffffffff81d9ad5b)
Location: include/net/sock.h:2374
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff81db12d5)
Location: include/net/sock.h:2374
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff81f4a802)
Location: include/net/sock.h:2374
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_write_space
```
```
In net/mptcp/subflow.c (ffffffff81fffb3f)
Location: include/net/sock.h:2374
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_state_change
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
In net/core/sock.c (ffffffff81e095db)
Location: include/net/sock.h:2362
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff81e217e5)
Location: include/net/sock.h:2362
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff81faa4a2)
Location: include/net/sock.h:2362
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_write_space
```
```
In net/mptcp/subflow.c (ffffffff8207badd)
Location: include/net/sock.h:2362
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_state_change
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
In net/core/sock.c (ffffffff81ec5fcb)
Location: include/net/sock.h:2352
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff81edf705)
Location: include/net/sock.h:2352
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff820778c2)
Location: include/net/sock.h:2352
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_write_space
```
```
In net/mptcp/subflow.c (ffffffff82150edd)
Location: include/net/sock.h:2352
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_state_change
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
In net/core/sock.c (ffff800010baa4f4)
Location: include/net/sock.h:2096
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffff800010bbd8d0)
Location: include/net/sock.h:2096
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffff800010cef354)
Location: include/net/sock.h:2096
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_write_space
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
In net/core/sock.c (c0cc9044)
Location: include/net/sock.h:2096
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (c0cd9a14)
Location: include/net/sock.h:2096
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (c0df7fa8)
Location: include/net/sock.h:2096
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_write_space
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
In net/core/sock.c (c000000000c80904)
Location: include/net/sock.h:2096
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (c000000000c96c68)
Location: include/net/sock.h:2096
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (c000000000e14ff0)
Location: include/net/sock.h:2096
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_write_space
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
In net/core/sock.c (ffffffe00073deaa)
Location: include/net/sock.h:2096
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffe00074bcfa)
Location: include/net/sock.h:2096
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffe00083c39c)
Location: include/net/sock.h:2096
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_write_space
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
In net/core/sock.c (ffffffff818b2dc6)
Location: include/net/sock.h:2096
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff818c2c49)
Location: include/net/sock.h:2096
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff819cf3dd)
Location: include/net/sock.h:2096
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_write_space
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
In net/core/sock.c (ffffffff8186cd16)
Location: include/net/sock.h:2096
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff8187cb89)
Location: include/net/sock.h:2096
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff8198c19d)
Location: include/net/sock.h:2096
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_write_space
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
In net/core/sock.c (ffffffff81903dc6)
Location: include/net/sock.h:2096
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff81913c49)
Location: include/net/sock.h:2096
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff81a39e5d)
Location: include/net/sock.h:2096
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_write_space
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
In net/core/sock.c (ffffffff81924dcb)
Location: include/net/sock.h:2096
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_def_error_report
  - net/core/sock.c:sock_def_wakeup
```
```
In net/core/stream.c (ffffffff81934dde)
Location: include/net/sock.h:2096
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_write_space
```
```
In net/unix/af_unix.c (ffffffff81a464a2)
Location: include/net/sock.h:2096
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_write_space
```
</details>
</li>
</ul>

## Differences
