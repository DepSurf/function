# Function: <code>SYSC_mq_getsetattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int SYSC_mq_getsetattr(mqd_t mqdes, const struct mq_attr *u_mqstat, struct mq_attr *u_omqstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8132c1c0)
Location: ipc/mqueue.c:1321
Inline: False
Direct callers:
  - ipc/mqueue.c:SyS_mq_getsetattr
```
**Symbols:**

```
ffffffff8132c1c0-ffffffff8132c3da: SYSC_mq_getsetattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int SYSC_mq_getsetattr(mqd_t mqdes, const struct mq_attr *u_mqstat, struct mq_attr *u_omqstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81360e50)
Location: ipc/mqueue.c:1319
Inline: False
Direct callers:
  - ipc/mqueue.c:SyS_mq_getsetattr
```
**Symbols:**

```
ffffffff81360e50-ffffffff81361078: SYSC_mq_getsetattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int SYSC_mq_getsetattr(mqd_t mqdes, const struct mq_attr *u_mqstat, struct mq_attr *u_omqstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81377660)
Location: ipc/mqueue.c:1319
Inline: False
Direct callers:
  - ipc/mqueue.c:SyS_mq_getsetattr
```
**Symbols:**

```
ffffffff81377660-ffffffff8137787e: SYSC_mq_getsetattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int SYSC_mq_getsetattr(mqd_t mqdes, const struct mq_attr *u_mqstat, struct mq_attr *u_omqstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8138b360)
Location: ipc/mqueue.c:1398
Inline: False
Direct callers:
  - ipc/mqueue.c:SyS_mq_getsetattr
```
**Symbols:**

```
ffffffff8138b360-ffffffff8138b40e: SYSC_mq_getsetattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int SYSC_mq_getsetattr(mqd_t mqdes, const struct mq_attr *u_mqstat, struct mq_attr *u_omqstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff813b06f0)
Location: ipc/mqueue.c:1398
Inline: False
Direct callers:
  - ipc/mqueue.c:SyS_mq_getsetattr
```
**Symbols:**

```
ffffffff813b06f0-ffffffff813b079e: SYSC_mq_getsetattr (STB_LOCAL)
```
</details>
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
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
