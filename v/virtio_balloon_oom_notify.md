# Function: <code>virtio_balloon_oom_notify</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int virtio_balloon_oom_notify(struct notifier_block *nb, long unsigned int dummy, void *parm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff817103f0)
Location: drivers/virtio/virtio_balloon.c:861
Inline: False
```
**Symbols:**

```
ffffffff817103f0-ffffffff8171042a: virtio_balloon_oom_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int virtio_balloon_oom_notify(struct notifier_block *nb, long unsigned int dummy, void *parm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff8172d7f0)
Location: drivers/virtio/virtio_balloon.c:853
Inline: False
```
**Symbols:**

```
ffffffff8172d7f0-ffffffff8172d881: virtio_balloon_oom_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int virtio_balloon_oom_notify(struct notifier_block *nb, long unsigned int dummy, void *parm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff81711730)
Location: drivers/virtio/virtio_balloon.c:853
Inline: False
```
**Symbols:**

```
ffffffff81711730-ffffffff817117c1: virtio_balloon_oom_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int virtio_balloon_oom_notify(struct notifier_block *nb, long unsigned int dummy, void *parm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff8178e190)
Location: drivers/virtio/virtio_balloon.c:853
Inline: False
```
**Symbols:**

```
ffffffff8178e190-ffffffff8178e221: virtio_balloon_oom_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int virtio_balloon_oom_notify(struct notifier_block *nb, long unsigned int dummy, void *parm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff818c60c0)
Location: drivers/virtio/virtio_balloon.c:853
Inline: False
```
**Symbols:**

```
ffffffff818c60c0-ffffffff818c615d: virtio_balloon_oom_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int virtio_balloon_oom_notify(struct notifier_block *nb, long unsigned int dummy, void *parm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff81a169e0)
Location: drivers/virtio/virtio_balloon.c:834
Inline: False
```
**Symbols:**

```
ffffffff81a169e0-ffffffff81a16a7d: virtio_balloon_oom_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int virtio_balloon_oom_notify(struct notifier_block *nb, long unsigned int dummy, void *parm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff81a5fa70)
Location: drivers/virtio/virtio_balloon.c:834
Inline: False
```
**Symbols:**

```
ffffffff81a5fa70-ffffffff81a5fb0d: virtio_balloon_oom_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int virtio_balloon_oom_notify(struct notifier_block *nb, long unsigned int dummy, void *parm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff81ab2280)
Location: drivers/virtio/virtio_balloon.c:871
Inline: False
```
**Symbols:**

```
ffffffff81ab2280-ffffffff81ab231d: virtio_balloon_oom_notify (STB_LOCAL)
```
</details>
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
