# Function: <code>ptr_to_compat</code>

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
In arch/x86/kernel/signal.c (0)
Location: arch/x86/include/asm/compat.h:291
Inline: True
```
```
In arch/x86/kernel/signal_compat.c (0)
Location: arch/x86/include/asm/compat.h:291
Inline: True
```
```
In arch/x86/ia32/ia32_signal.c (0)
Location: arch/x86/include/asm/compat.h:291
Inline: True
```
```
In kernel/signal.c (0)
Location: arch/x86/include/asm/compat.h:291
Inline: True
```
```
In kernel/futex_compat.c (0)
Location: arch/x86/include/asm/compat.h:291
Inline: True
```
```
In fs/fuse/file.c (0)
Location: arch/x86/include/asm/compat.h:291
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: arch/x86/include/asm/compat.h:291
Inline: True
```
```
In net/wireless/wext-core.c (0)
Location: arch/x86/include/asm/compat.h:291
Inline: True
```
```
In net/wireless/wext-priv.c (0)
Location: arch/x86/include/asm/compat.h:291
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
In arch/x86/kernel/signal.c (ffffffff8102da50)
Location: arch/x86/include/asm/compat.h:302
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/signal_compat.c (ffffffff8102df3e)
Location: arch/x86/include/asm/compat.h:302
Inline: True
Inline callers:
  - arch/x86/kernel/signal_compat.c:copy_siginfo_to_user32
  - arch/x86/kernel/signal_compat.c:copy_siginfo_to_user32
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81079b93)
Location: arch/x86/include/asm/compat.h:302
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
```
```
In kernel/signal.c (ffffffff81094de8)
Location: arch/x86/include/asm/compat.h:302
Inline: True
Inline callers:
  - kernel/signal.c:__compat_save_altstack
```
```
In kernel/futex_compat.c (0)
Location: arch/x86/include/asm/compat.h:302
Inline: True
```
```
In fs/fuse/file.c (0)
Location: arch/x86/include/asm/compat.h:302
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: arch/x86/include/asm/compat.h:302
Inline: True
```
```
In net/wireless/wext-core.c (ffffffff8187c07a)
Location: arch/x86/include/asm/compat.h:302
Inline: True
Inline callers:
  - net/wireless/wext-core.c:compat_standard_call
```
```
In net/wireless/wext-priv.c (ffffffff8187cd7b)
Location: arch/x86/include/asm/compat.h:302
Inline: True
Inline callers:
  - net/wireless/wext-priv.c:compat_private_call
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
In arch/x86/kernel/signal.c (ffffffff8102d8c0)
Location: arch/x86/include/asm/compat.h:300
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/signal_compat.c (ffffffff8102de00)
Location: arch/x86/include/asm/compat.h:300
Inline: True
Inline callers:
  - arch/x86/kernel/signal_compat.c:__copy_siginfo_to_user32
  - arch/x86/kernel/signal_compat.c:__copy_siginfo_to_user32
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8107d983)
Location: arch/x86/include/asm/compat.h:300
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
```
```
In kernel/signal.c (ffffffff81099df7)
Location: arch/x86/include/asm/compat.h:300
Inline: True
Inline callers:
  - kernel/signal.c:__compat_save_altstack
```
```
In kernel/futex_compat.c (0)
Location: arch/x86/include/asm/compat.h:300
Inline: True
```
```
In fs/fuse/file.c (0)
Location: arch/x86/include/asm/compat.h:300
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: arch/x86/include/asm/compat.h:300
Inline: True
```
```
In net/wireless/wext-core.c (ffffffff818b093a)
Location: arch/x86/include/asm/compat.h:300
Inline: True
Inline callers:
  - net/wireless/wext-core.c:compat_standard_call
```
```
In net/wireless/wext-priv.c (ffffffff818b162b)
Location: arch/x86/include/asm/compat.h:300
Inline: True
Inline callers:
  - net/wireless/wext-priv.c:compat_private_call
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
In arch/x86/kernel/signal.c (ffffffff8102b9fa)
Location: arch/x86/include/asm/compat.h:299
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/signal_compat.c (ffffffff8102c080)
Location: arch/x86/include/asm/compat.h:299
Inline: True
Inline callers:
  - arch/x86/kernel/signal_compat.c:__copy_siginfo_to_user32
  - arch/x86/kernel/signal_compat.c:__copy_siginfo_to_user32
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8107c153)
Location: arch/x86/include/asm/compat.h:299
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
```
```
In kernel/signal.c (ffffffff81096e97)
Location: arch/x86/include/asm/compat.h:299
Inline: True
Inline callers:
  - kernel/signal.c:__compat_save_altstack
```
```
In kernel/futex_compat.c (0)
Location: arch/x86/include/asm/compat.h:299
Inline: True
```
```
In fs/fuse/file.c (0)
Location: arch/x86/include/asm/compat.h:299
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: arch/x86/include/asm/compat.h:299
Inline: True
```
```
In net/wireless/wext-core.c (ffffffff818d72ba)
Location: arch/x86/include/asm/compat.h:299
Inline: True
Inline callers:
  - net/wireless/wext-core.c:compat_standard_call
```
```
In net/wireless/wext-priv.c (ffffffff818d7ff0)
Location: arch/x86/include/asm/compat.h:299
Inline: True
Inline callers:
  - net/wireless/wext-priv.c:compat_private_call
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
In arch/x86/kernel/signal.c (ffffffff8102c720)
Location: arch/x86/include/asm/compat.h:300
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/kernel/signal_compat.c (ffffffff8102cd85)
Location: arch/x86/include/asm/compat.h:300
Inline: True
Inline callers:
  - arch/x86/kernel/signal_compat.c:__copy_siginfo_to_user32
  - arch/x86/kernel/signal_compat.c:__copy_siginfo_to_user32
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81082853)
Location: arch/x86/include/asm/compat.h:300
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
```
```
In kernel/signal.c (ffffffff8109dc37)
Location: arch/x86/include/asm/compat.h:300
Inline: True
Inline callers:
  - kernel/signal.c:__compat_save_altstack
```
```
In kernel/futex_compat.c (0)
Location: arch/x86/include/asm/compat.h:300
Inline: True
```
```
In fs/fuse/file.c (0)
Location: arch/x86/include/asm/compat.h:300
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: arch/x86/include/asm/compat.h:300
Inline: True
```
```
In net/wireless/wext-core.c (ffffffff8195ce8a)
Location: arch/x86/include/asm/compat.h:300
Inline: True
Inline callers:
  - net/wireless/wext-core.c:compat_standard_call
```
```
In net/wireless/wext-priv.c (ffffffff8195dbd2)
Location: arch/x86/include/asm/compat.h:300
Inline: True
Inline callers:
  - net/wireless/wext-priv.c:compat_private_call
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
In arch/x86/kernel/signal.c (ffffffff8102d802)
Location: arch/x86/include/asm/compat.h:207
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81085f13)
Location: arch/x86/include/asm/compat.h:207
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_sigcontext
```
```
In kernel/signal.c (ffffffff810a27aa)
Location: arch/x86/include/asm/compat.h:207
Inline: True
Inline callers:
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:__copy_siginfo_to_user32
```
```
In kernel/futex_compat.c (ffffffff8112be08)
Location: arch/x86/include/asm/compat.h:207
Inline: True
Inline callers:
  - kernel/futex_compat.c:__x32_compat_sys_get_robust_list
  - kernel/futex_compat.c:__ia32_compat_sys_get_robust_list
  - kernel/futex_compat.c:compat_exit_robust_list
```
```
In fs/fuse/file.c (ffffffff813c8476)
Location: arch/x86/include/asm/compat.h:207
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
```
```
In drivers/usb/core/devio.c (ffffffff8176b2b0)
Location: arch/x86/include/asm/compat.h:207
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:processcompl_compat
```
```
In net/wireless/wext-core.c (ffffffff819b66a0)
Location: arch/x86/include/asm/compat.h:207
Inline: True
Inline callers:
  - net/wireless/wext-core.c:compat_standard_call
```
```
In net/wireless/wext-priv.c (ffffffff819b73de)
Location: arch/x86/include/asm/compat.h:207
Inline: True
Inline callers:
  - net/wireless/wext-priv.c:compat_private_call
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
In arch/x86/kernel/signal.c (ffffffff8102ea46)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8108cca3)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_sigcontext
```
```
In kernel/signal.c (ffffffff810ab377)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:__copy_siginfo_to_user32
```
```
In kernel/futex.c (ffffffff811338d8)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - kernel/futex.c:__x32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_compat_sys_get_robust_list
  - kernel/futex.c:compat_exit_robust_list
```
```
In fs/fuse/file.c (ffffffff813e1698)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
```
```
In drivers/tty/tty_io.c (0)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:compat_tty_tiocgserial
```
```
In drivers/usb/core/devio.c (ffffffff8178f840)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:processcompl_compat
```
```
In net/wireless/wext-core.c (ffffffff819ed960)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - net/wireless/wext-core.c:compat_standard_call
```
```
In net/wireless/wext-priv.c (ffffffff819ee69e)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - net/wireless/wext-priv.c:compat_private_call
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
In arch/x86/kernel/signal.c (ffffffff81030658)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:x32_setup_rt_frame
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81090b66)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_sigcontext
```
```
In kernel/signal.c (ffffffff810b0867)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:__copy_siginfo_to_user32
```
```
In kernel/futex.c (ffffffff8113e92a)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - kernel/futex.c:__x32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_compat_sys_get_robust_list
  - kernel/futex.c:compat_exit_robust_list
```
```
In fs/fuse/file.c (ffffffff8140d36a)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
```
```
In drivers/tty/tty_io.c (ffffffff8165fdf5)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:compat_tty_tiocgserial
```
```
In drivers/usb/core/devio.c (ffffffff817cd644)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:processcompl_compat
```
```
In net/wireless/wext-core.c (ffffffff81a5cae6)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - net/wireless/wext-core.c:compat_standard_call
```
```
In net/wireless/wext-priv.c (ffffffff81a5d8de)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - net/wireless/wext-priv.c:compat_private_call
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
In arch/x86/kernel/signal.c (ffffffff81031157)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81091866)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_sigcontext
```
```
In kernel/signal.c (ffffffff810b7375)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:__copy_siginfo_to_user32
```
```
In kernel/futex.c (ffffffff8114a49a)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - kernel/futex.c:__x32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_compat_sys_get_robust_list
  - kernel/futex.c:futex_cleanup
```
```
In fs/fuse/file.c (ffffffff81428771)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
```
```
In drivers/tty/tty_io.c (ffffffff81682443)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:compat_tty_tiocgserial
```
```
In drivers/usb/core/devio.c (ffffffff817fded2)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:processcompl_compat
```
```
In net/wireless/wext-core.c (ffffffff81a93766)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - net/wireless/wext-core.c:compat_standard_call
```
```
In net/wireless/wext-priv.c (ffffffff81a9450e)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - net/wireless/wext-priv.c:compat_private_call
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
In arch/x86/kernel/signal.c (ffffffff81033373)
Location: include/linux/compat.h:953
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:x32_setup_rt_frame
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81096fec)
Location: include/linux/compat.h:953
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
```
In kernel/signal.c (ffffffff810beec3)
Location: include/linux/compat.h:953
Inline: True
Inline callers:
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
```
```
In kernel/futex.c (ffffffff8115afba)
Location: include/linux/compat.h:953
Inline: True
Inline callers:
  - kernel/futex.c:__x32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_compat_sys_get_robust_list
  - kernel/futex.c:compat_exit_robust_list
```
```
In fs/fuse/file.c (ffffffff8147643e)
Location: include/linux/compat.h:953
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
```
```
In drivers/tty/tty_io.c (ffffffff817339a3)
Location: include/linux/compat.h:953
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:compat_tty_tiocgserial
```
```
In drivers/usb/core/devio.c (ffffffff818ce5e5)
Location: include/linux/compat.h:953
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:processcompl_compat
```
```
In net/wireless/wext-core.c (ffffffff81b8ebf4)
Location: include/linux/compat.h:953
Inline: True
Inline callers:
  - net/wireless/wext-core.c:compat_standard_call
```
```
In net/wireless/wext-priv.c (ffffffff81b8faf7)
Location: include/linux/compat.h:953
Inline: True
Inline callers:
  - net/wireless/wext-priv.c:compat_private_call
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
In arch/x86/kernel/signal.c (ffffffff81033dbb)
Location: include/linux/compat.h:967
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:x32_setup_rt_frame
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81096245)
Location: include/linux/compat.h:967
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
```
In kernel/signal.c (ffffffff810ba221)
Location: include/linux/compat.h:967
Inline: True
Inline callers:
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_rt_sigaction
  - kernel/signal.c:__do_compat_sys_rt_sigaction
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
```
```
In kernel/futex.c (ffffffff811570ed)
Location: include/linux/compat.h:967
Inline: True
Inline callers:
  - kernel/futex.c:__x32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_compat_sys_get_robust_list
  - kernel/futex.c:compat_exit_robust_list
```
```
In fs/fuse/file.c (ffffffff81490ea5)
Location: include/linux/compat.h:967
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
```
```
In drivers/tty/tty_io.c (ffffffff8174fae3)
Location: include/linux/compat.h:967
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:compat_tty_tiocgserial
```
```
In drivers/usb/core/devio.c (ffffffff818d9555)
Location: include/linux/compat.h:967
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:processcompl_compat
```
```
In net/wireless/wext-core.c (ffffffff81b9e8a4)
Location: include/linux/compat.h:967
Inline: True
Inline callers:
  - net/wireless/wext-core.c:compat_standard_call
```
```
In net/wireless/wext-priv.c (ffffffff81b9f737)
Location: include/linux/compat.h:967
Inline: True
Inline callers:
  - net/wireless/wext-priv.c:compat_private_call
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
In arch/x86/kernel/signal.c (ffffffff810358b9)
Location: include/linux/compat.h:1005
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:x32_setup_rt_frame
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81096b32)
Location: include/linux/compat.h:1005
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
```
In kernel/signal.c (ffffffff810bbd8c)
Location: include/linux/compat.h:1005
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_rt_sigaction
  - kernel/signal.c:__do_compat_sys_rt_sigaction
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
```
```
In kernel/futex.c (ffffffff8115850d)
Location: include/linux/compat.h:1005
Inline: True
Inline callers:
  - kernel/futex.c:__x32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_compat_sys_get_robust_list
  - kernel/futex.c:compat_exit_robust_list
```
```
In fs/fuse/ioctl.c (ffffffff814a1b2a)
Location: include/linux/compat.h:1005
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_do_ioctl
```
```
In drivers/tty/tty_io.c (ffffffff81733a49)
Location: include/linux/compat.h:1005
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:compat_tty_tiocgserial
```
```
In drivers/usb/core/devio.c (ffffffff818bc6e6)
Location: include/linux/compat.h:1005
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:processcompl_compat
```
```
In net/wireless/wext-core.c (ffffffff81b8d984)
Location: include/linux/compat.h:1005
Inline: True
Inline callers:
  - net/wireless/wext-core.c:compat_standard_call
```
```
In net/wireless/wext-priv.c (ffffffff81b8e807)
Location: include/linux/compat.h:1005
Inline: True
Inline callers:
  - net/wireless/wext-priv.c:compat_private_call
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
In arch/x86/kernel/signal.c (ffffffff8103ab99)
Location: include/linux/compat.h:980
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:x32_setup_rt_frame
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810a6ad2)
Location: include/linux/compat.h:980
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
```
In kernel/signal.c (ffffffff810ce7ec)
Location: include/linux/compat.h:980
Inline: True
Inline callers:
  - kernel/signal.c:__x64_compat_sys_sigaction
  - kernel/signal.c:__x64_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__x64_compat_sys_rt_sigaction
  - kernel/signal.c:__x64_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
```
```
In kernel/futex.c (ffffffff8117d34d)
Location: include/linux/compat.h:980
Inline: True
Inline callers:
  - kernel/futex.c:__x64_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_compat_sys_get_robust_list
  - kernel/futex.c:compat_exit_robust_list
```
```
In fs/fuse/ioctl.c (ffffffff814f9c04)
Location: include/linux/compat.h:980
Inline: True
Inline callers:
  - fs/fuse/ioctl.c:fuse_do_ioctl
```
```
In drivers/tty/tty_io.c (ffffffff817b43b9)
Location: include/linux/compat.h:980
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:compat_tty_tiocgserial
```
```
In drivers/usb/core/devio.c (ffffffff81952707)
Location: include/linux/compat.h:980
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:processcompl_compat
```
```
In net/wireless/wext-core.c (ffffffff81c59df4)
Location: include/linux/compat.h:980
Inline: True
Inline callers:
  - net/wireless/wext-core.c:compat_standard_call
```
```
In net/wireless/wext-priv.c (ffffffff81c5ad97)
Location: include/linux/compat.h:980
Inline: True
Inline callers:
  - net/wireless/wext-priv.c:compat_private_call
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
In arch/x86/ia32/ia32_signal.c (ffffffff810bbddc)
Location: include/linux/compat.h:1049
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
```
In kernel/signal.c (ffffffff810e655e)
Location: include/linux/compat.h:1049
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
```
```
In kernel/futex/core.c (ffffffff811b304f)
Location: include/linux/compat.h:1049
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_cleanup
```
```
In kernel/futex/syscalls.c (ffffffff811b373e)
Location: include/linux/compat.h:1049
Inline: True
Inline callers:
  - kernel/futex/syscalls.c:__ia32_compat_sys_get_robust_list
```
```
In fs/fuse/ioctl.c (0)
Location: include/linux/compat.h:1049
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff818f0143)
Location: include/linux/compat.h:1049
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:compat_tty_tiocgserial
```
```
In drivers/usb/core/devio.c (ffffffff81aabe20)
Location: include/linux/compat.h:1049
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:processcompl_compat
```
```
In net/wireless/wext-core.c (ffffffff81dfb671)
Location: include/linux/compat.h:1049
Inline: True
Inline callers:
  - net/wireless/wext-core.c:compat_standard_call
```
```
In net/wireless/wext-priv.c (ffffffff81dfc8aa)
Location: include/linux/compat.h:1049
Inline: True
Inline callers:
  - net/wireless/wext-priv.c:compat_private_call
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
In arch/x86/kernel/signal_32.c (ffffffff81055d97)
Location: include/linux/compat.h:1047
Inline: True
Inline callers:
  - arch/x86/kernel/signal_32.c:ia32_setup_rt_frame
  - arch/x86/kernel/signal_32.c:ia32_setup_rt_frame
  - arch/x86/kernel/signal_32.c:ia32_setup_rt_frame
  - arch/x86/kernel/signal_32.c:ia32_setup_rt_frame
  - arch/x86/kernel/signal_32.c:ia32_setup_rt_frame
  - arch/x86/kernel/signal_32.c:ia32_setup_frame
  - arch/x86/kernel/signal_32.c:ia32_setup_frame
```
```
In kernel/signal.c (ffffffff8110718e)
Location: include/linux/compat.h:1047
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
```
```
In kernel/futex/core.c (ffffffff811f3f3f)
Location: include/linux/compat.h:1047
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_cleanup
```
```
In kernel/futex/syscalls.c (ffffffff811f472e)
Location: include/linux/compat.h:1047
Inline: True
Inline callers:
  - kernel/futex/syscalls.c:__ia32_compat_sys_get_robust_list
```
```
In fs/fuse/ioctl.c (0)
Location: include/linux/compat.h:1047
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff81a48253)
Location: include/linux/compat.h:1047
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:compat_tty_tiocgserial
```
```
In drivers/usb/core/devio.c (ffffffff81c33330)
Location: include/linux/compat.h:1047
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:processcompl_compat
```
```
In net/wireless/wext-core.c (ffffffff81fd0051)
Location: include/linux/compat.h:1047
Inline: True
Inline callers:
  - net/wireless/wext-core.c:compat_standard_call
```
```
In net/wireless/wext-priv.c (ffffffff81fd129a)
Location: include/linux/compat.h:1047
Inline: True
Inline callers:
  - net/wireless/wext-priv.c:compat_private_call
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
In arch/x86/kernel/signal_32.c (ffffffff81056d40)
Location: include/linux/compat.h:983
Inline: True
Inline callers:
  - arch/x86/kernel/signal_32.c:ia32_setup_rt_frame
  - arch/x86/kernel/signal_32.c:ia32_setup_rt_frame
  - arch/x86/kernel/signal_32.c:ia32_setup_rt_frame
  - arch/x86/kernel/signal_32.c:ia32_setup_rt_frame
  - arch/x86/kernel/signal_32.c:ia32_setup_rt_frame
  - arch/x86/kernel/signal_32.c:ia32_setup_frame
  - arch/x86/kernel/signal_32.c:ia32_setup_frame
```
```
In kernel/signal.c (ffffffff81113475)
Location: include/linux/compat.h:983
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
```
```
In kernel/futex/core.c (ffffffff812086cf)
Location: include/linux/compat.h:983
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_cleanup
```
```
In kernel/futex/syscalls.c (ffffffff81208ebe)
Location: include/linux/compat.h:983
Inline: True
Inline callers:
  - kernel/futex/syscalls.c:__ia32_compat_sys_get_robust_list
```
```
In fs/fuse/ioctl.c (0)
Location: include/linux/compat.h:983
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff81a92373)
Location: include/linux/compat.h:983
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:compat_tty_tiocgserial
```
```
In drivers/usb/core/devio.c (ffffffff81c9adbe)
Location: include/linux/compat.h:983
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:processcompl_compat
```
```
In net/wireless/wext-core.c (ffffffff8204bb11)
Location: include/linux/compat.h:983
Inline: True
Inline callers:
  - net/wireless/wext-core.c:compat_standard_call
```
```
In net/wireless/wext-priv.c (ffffffff8204cea2)
Location: include/linux/compat.h:983
Inline: True
Inline callers:
  - net/wireless/wext-priv.c:compat_private_call
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
In arch/x86/kernel/signal_32.c (ffffffff8105df90)
Location: include/linux/compat.h:982
Inline: True
Inline callers:
  - arch/x86/kernel/signal_32.c:ia32_setup_rt_frame
  - arch/x86/kernel/signal_32.c:ia32_setup_rt_frame
  - arch/x86/kernel/signal_32.c:ia32_setup_rt_frame
  - arch/x86/kernel/signal_32.c:ia32_setup_rt_frame
  - arch/x86/kernel/signal_32.c:ia32_setup_rt_frame
  - arch/x86/kernel/signal_32.c:ia32_setup_frame
  - arch/x86/kernel/signal_32.c:ia32_setup_frame
```
```
In kernel/signal.c (ffffffff8111ce65)
Location: include/linux/compat.h:982
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
  - kernel/signal.c:copy_siginfo_to_external32
```
```
In kernel/futex/core.c (ffffffff8121f55f)
Location: include/linux/compat.h:982
Inline: True
Inline callers:
  - kernel/futex/core.c:futex_cleanup
```
```
In kernel/futex/syscalls.c (ffffffff8121fd5e)
Location: include/linux/compat.h:982
Inline: True
Inline callers:
  - kernel/futex/syscalls.c:__ia32_compat_sys_get_robust_list
```
```
In fs/fuse/ioctl.c (0)
Location: include/linux/compat.h:982
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff81ae4d53)
Location: include/linux/compat.h:982
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:compat_tty_tiocgserial
```
```
In drivers/usb/core/devio.c (ffffffff81d4f97f)
Location: include/linux/compat.h:982
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:processcompl_compat
```
```
In net/wireless/wext-core.c (ffffffff8211df91)
Location: include/linux/compat.h:982
Inline: True
Inline callers:
  - net/wireless/wext-core.c:compat_standard_call
```
```
In net/wireless/wext-priv.c (ffffffff8211f342)
Location: include/linux/compat.h:982
Inline: True
Inline callers:
  - net/wireless/wext-priv.c:compat_private_call
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
In arch/arm64/kernel/signal32.c (ffff80001009dec8)
Location: arch/arm64/include/asm/compat.h:128
Inline: True
```
```
In kernel/signal.c (ffff8000101132e4)
Location: arch/arm64/include/asm/compat.h:128
Inline: True
Inline callers:
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_rt_sigaction
  - kernel/signal.c:__do_compat_sys_rt_sigaction
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:copy_siginfo_to_user32
  - kernel/signal.c:copy_siginfo_to_user32
  - kernel/signal.c:copy_siginfo_to_user32
  - kernel/signal.c:copy_siginfo_to_user32
  - kernel/signal.c:copy_siginfo_to_user32
  - kernel/signal.c:copy_siginfo_to_user32
  - kernel/signal.c:copy_siginfo_to_user32
```
```
In kernel/futex.c (ffff8000101b73e8)
Location: arch/arm64/include/asm/compat.h:128
Inline: True
Inline callers:
  - kernel/futex.c:__arm64_compat_sys_get_robust_list
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
```
```
In fs/fuse/file.c (ffff80001050ab7c)
Location: arch/arm64/include/asm/compat.h:128
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
```
```
In drivers/tty/tty_io.c (0)
Location: arch/arm64/include/asm/compat.h:128
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:compat_tty_tiocgserial
```
```
In drivers/usb/core/devio.c (ffff800010a31830)
Location: arch/arm64/include/asm/compat.h:128
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:processcompl_compat
```
```
In net/wireless/wext-core.c (ffff800010d61958)
Location: arch/arm64/include/asm/compat.h:128
Inline: True
Inline callers:
  - net/wireless/wext-core.c:compat_standard_call
```
```
In net/wireless/wext-priv.c (ffff800010d62cc8)
Location: arch/arm64/include/asm/compat.h:128
Inline: True
Inline callers:
  - net/wireless/wext-priv.c:compat_private_call
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/signal_32.c (c00000000001f7d8)
Location: arch/powerpc/include/asm/compat.h:111
Inline: True
Inline callers:
  - arch/powerpc/kernel/signal_32.c:handle_signal32
  - arch/powerpc/kernel/signal_32.c:handle_signal32
  - arch/powerpc/kernel/signal_32.c:__do_compat_sys_swapcontext
  - arch/powerpc/kernel/signal_32.c:handle_rt_signal32
```
```
In kernel/signal.c (c00000000015b018)
Location: arch/powerpc/include/asm/compat.h:111
Inline: True
Inline callers:
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__do_compat_sys_sigaction
  - kernel/signal.c:__se_compat_sys_rt_sigaction
  - kernel/signal.c:__se_compat_sys_rt_sigaction
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:copy_siginfo_to_user32
  - kernel/signal.c:copy_siginfo_to_user32
  - kernel/signal.c:copy_siginfo_to_user32
  - kernel/signal.c:copy_siginfo_to_user32
  - kernel/signal.c:copy_siginfo_to_user32
  - kernel/signal.c:copy_siginfo_to_user32
  - kernel/signal.c:copy_siginfo_to_user32
```
```
In kernel/futex.c (c00000000021c6d0)
Location: arch/powerpc/include/asm/compat.h:111
Inline: True
Inline callers:
  - kernel/futex.c:__se_compat_sys_get_robust_list
  - kernel/futex.c:futex_cleanup
```
```
In fs/fuse/file.c (c000000000652f18)
Location: arch/powerpc/include/asm/compat.h:111
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
```
```
In drivers/tty/tty_io.c (c0000000008ed1c0)
Location: arch/powerpc/include/asm/compat.h:111
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:compat_tty_tiocgserial
```
```
In drivers/usb/core/devio.c (c000000000aefd44)
Location: arch/powerpc/include/asm/compat.h:111
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:processcompl_compat
```
```
In net/wireless/wext-core.c (c000000000e9ccb8)
Location: arch/powerpc/include/asm/compat.h:111
Inline: True
Inline callers:
  - net/wireless/wext-core.c:compat_standard_call
```
```
In net/wireless/wext-priv.c (c000000000e9e048)
Location: arch/powerpc/include/asm/compat.h:111
Inline: True
Inline callers:
  - net/wireless/wext-priv.c:compat_private_call
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In arch/x86/kernel/signal.c (ffffffff810312b7)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81090826)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_sigcontext
```
```
In kernel/signal.c (ffffffff810b16e5)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:__copy_siginfo_to_user32
```
```
In kernel/futex.c (ffffffff81142aba)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - kernel/futex.c:__x32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_compat_sys_get_robust_list
  - kernel/futex.c:futex_cleanup
```
```
In fs/fuse/file.c (ffffffff81420d51)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
```
```
In drivers/tty/tty_io.c (ffffffff81647ec3)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:compat_tty_tiocgserial
```
```
In drivers/usb/core/devio.c (ffffffff817b62b2)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:processcompl_compat
```
```
In net/wireless/wext-core.c (ffffffff81a32df6)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - net/wireless/wext-core.c:compat_standard_call
```
```
In net/wireless/wext-priv.c (ffffffff81a3389e)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - net/wireless/wext-priv.c:compat_private_call
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
In arch/x86/kernel/signal.c (ffffffff81020cc4)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8107f336)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_sigcontext
```
```
In kernel/signal.c (ffffffff810a0005)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:__copy_siginfo_to_user32
```
```
In kernel/futex.c (ffffffff81135e1a)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - kernel/futex.c:__x32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_compat_sys_get_robust_list
  - kernel/futex.c:futex_cleanup
```
```
In fs/fuse/file.c (ffffffff814117d1)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
```
```
In drivers/tty/tty_io.c (ffffffff81628323)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:compat_tty_tiocgserial
```
```
In drivers/usb/core/devio.c (ffffffff817a7cd2)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:processcompl_compat
```
```
In net/wireless/wext-core.c (ffffffff819effb6)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - net/wireless/wext-core.c:compat_standard_call
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
In arch/x86/kernel/signal.c (ffffffff81031117)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810907d6)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_sigcontext
```
```
In kernel/signal.c (ffffffff810b0c45)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:__copy_siginfo_to_user32
```
```
In kernel/futex.c (ffffffff8114096a)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - kernel/futex.c:__x32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_compat_sys_get_robust_list
  - kernel/futex.c:futex_cleanup
```
```
In fs/fuse/file.c (ffffffff8141cef1)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
```
```
In drivers/tty/tty_io.c (ffffffff81676283)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:compat_tty_tiocgserial
```
```
In drivers/usb/core/devio.c (ffffffff817f2d52)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:processcompl_compat
```
```
In net/wireless/wext-core.c (ffffffff81a9e9a6)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - net/wireless/wext-core.c:compat_standard_call
```
```
In net/wireless/wext-priv.c (ffffffff81a9f74e)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - net/wireless/wext-priv.c:compat_private_call
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
In arch/x86/kernel/signal.c (ffffffff81031fc4)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81092bb6)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_sigcontext
```
```
In kernel/signal.c (ffffffff810b8f15)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__ia32_compat_sys_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__x32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__ia32_compat_sys_rt_sigaction
  - kernel/signal.c:__compat_save_altstack
  - kernel/signal.c:do_compat_sigaltstack
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:__copy_siginfo_to_user32
  - kernel/signal.c:__copy_siginfo_to_user32
```
```
In kernel/futex.c (ffffffff8114dbd2)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - kernel/futex.c:__x32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_compat_sys_get_robust_list
  - kernel/futex.c:futex_cleanup
```
```
In fs/fuse/file.c (ffffffff81433cd3)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_do_ioctl
```
```
In drivers/tty/tty_io.c (ffffffff816909a3)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:compat_tty_tiocgserial
```
```
In drivers/usb/core/devio.c (ffffffff8180cfd2)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:processcompl_compat
```
```
In net/wireless/wext-core.c (ffffffff81aaaba6)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - net/wireless/wext-core.c:compat_standard_call
```
```
In net/wireless/wext-priv.c (ffffffff81aab94e)
Location: arch/x86/include/asm/compat.h:192
Inline: True
Inline callers:
  - net/wireless/wext-priv.c:compat_private_call
```
</details>
</li>
</ul>

## Differences
