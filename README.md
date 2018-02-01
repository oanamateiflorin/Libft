# Libft
My own C library

# TRACE:

# = Host-specific information ====================================================
$> hostname; uname -msr
e2r3p9.42.fr
Darwin 16.7.0 x86_64
$> date
Fri Jan 19 16:28:01 CET 2018
$> gcc --version
Configured with: --prefix=/Applications/Xcode.app/Contents/Developer/usr --with-gxx-include-dir=/usr/include/c++/4.2.1
Apple LLVM version 9.0.0 (clang-900.0.38)
Target: x86_64-apple-darwin16.7.0
Thread model: posix
InstalledDir: /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin
$> clang --version
Apple LLVM version 9.0.0 (clang-900.0.38)
Target: x86_64-apple-darwin16.7.0
Thread model: posix
InstalledDir: /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin

= User files collection ========================================================
Collecting user files from Vogsphere
Repository URL: intra/2017/activities/libft/moana

= Git history ==================================================================
$> git -C /var/folders/tk/5cq7nj2s61135g_hgzylmxdm0000gq/T/tmpOXqef9/user log --pretty='%H - %an, %ad : %s'
0b84de15feb3460c8d7d2ca265b72dae58ff7d61 - Matei OANA, Thu Jan 18 18:44:54 2018 +0200 : no asa da, Doamne ajuta
809d397a08dc9e19245f857b97e23b81efb2cc27 - Matei OANA, Wed Jan 17 23:01:11 2018 +0200 : Doamne ajuta

= Collected files ==========================================
$> ls -lAR /var/folders/tk/5cq7nj2s61135g_hgzylmxdm0000gq/T/tmpOXqef9/user
total 704
-rw-r--r--  1 deepthought  deepthought  18436 Jan 19 16:28 .DS_Store
-rw-r--r--  1 deepthought  deepthought   4096 Jan 19 16:28 ._.DS_Store
-rwxr-xr-x  1 deepthought  deepthought   4096 Jan 19 16:28 ._ft_atoi.c
-rw-r--r--  1 deepthought  deepthought   4096 Jan 19 16:28 ._ft_div_mod.c
-rw-r--r--  1 deepthought  deepthought   4096 Jan 19 16:28 ._ft_range.c
-rwxr-xr-x  1 deepthought  deepthought   4096 Jan 19 16:28 ._ft_strcmp.c
-rwxr-xr-x  1 deepthought  deepthought   4096 Jan 19 16:28 ._ft_strequ.c
-rw-r--r--  1 deepthought  deepthought   4096 Jan 19 16:28 ._ft_strlcat.c
-rwxr-xr-x  1 deepthought  deepthought   4096 Jan 19 16:28 ._ft_strmapi.c
-rwxr-xr-x  1 deepthought  deepthought   4096 Jan 19 16:28 ._ft_strncmp.c
-rwxr-xr-x  1 deepthought  deepthought   4096 Jan 19 16:28 ._ft_strnequ.c
-rwxr-xr-x  1 deepthought  deepthought   4096 Jan 19 16:28 ._ft_strnstr.c
-rwxr-xr-x  1 deepthought  deepthought   4096 Jan 19 16:28 ._ft_strtrim.c
-rw-r--r--  1 deepthought  deepthought   4096 Jan 19 16:28 ._ft_ultimate_div_mod.c
-rw-r--r--  1 deepthought  deepthought   4096 Jan 19 16:28 ._ft_ultimate_range.c
-rwxr-xr-x  1 deepthought  deepthought   4096 Jan 19 16:28 ._libft.h
-rwxr-xr-x  1 deepthought  deepthought   1102 Jan 19 16:28 Makefile
-rw-r--r--  1 deepthought  deepthought   4148 Jan 19 16:28 __GIT_HISTORY
-rwxr-xr-x  1 deepthought  deepthought      6 Jan 19 16:28 auteur
-rwxr-xr-x  1 deepthought  deepthought   1406 Jan 19 16:28 ft_atoi.c
-rwxr-xr-x  1 deepthought  deepthought    973 Jan 19 16:28 ft_bzero.c
-rw-r--r--  1 deepthought  deepthought   1017 Jan 19 16:28 ft_div_mod.c
-rwxr-xr-x  1 deepthought  deepthought   1012 Jan 19 16:28 ft_isalnum.c
-rwxr-xr-x  1 deepthought  deepthought   1021 Jan 19 16:28 ft_isalpha.c
-rwxr-xr-x  1 deepthought  deepthought    990 Jan 19 16:28 ft_isascii.c
-rwxr-xr-x  1 deepthought  deepthought    992 Jan 19 16:28 ft_isdigit.c
-rwxr-xr-x  1 deepthought  deepthought    991 Jan 19 16:28 ft_isprint.c
-rwxr-xr-x  1 deepthought  deepthought   1328 Jan 19 16:28 ft_itoa.c
-rwxr-xr-x  1 deepthought  deepthought    993 Jan 19 16:28 ft_lstadd.c
-rwxr-xr-x  1 deepthought  deepthought   1059 Jan 19 16:28 ft_lstdel.c
-rwxr-xr-x  1 deepthought  deepthought   1054 Jan 19 16:28 ft_lstdelone.c
-rwxr-xr-x  1 deepthought  deepthought   1045 Jan 19 16:28 ft_lstiter.c
-rwxr-xr-x  1 deepthought  deepthought   1219 Jan 19 16:28 ft_lstmap.c
-rwxr-xr-x  1 deepthought  deepthought   1330 Jan 19 16:28 ft_lstnew.c
-rwxr-xr-x  1 deepthought  deepthought   1051 Jan 19 16:28 ft_memalloc.c
-rwxr-xr-x  1 deepthought  deepthought   1222 Jan 19 16:28 ft_memccpy.c
-rwxr-xr-x  1 deepthought  deepthought   1133 Jan 19 16:28 ft_memchr.c
-rwxr-xr-x  1 deepthought  deepthought   1227 Jan 19 16:28 ft_memcmp.c
-rwxr-xr-x  1 deepthought  deepthought   1142 Jan 19 16:28 ft_memcpy.c
-rwxr-xr-x  1 deepthought  deepthought    991 Jan 19 16:28 ft_memdel.c
-rwxr-xr-x  1 deepthought  deepthought   1155 Jan 19 16:28 ft_memmove.c
-rwxr-xr-x  1 deepthought  deepthought   1123 Jan 19 16:28 ft_memset.c
-rw-r--r--  1 deepthought  deepthought   1126 Jan 19 16:28 ft_printmatrice.c
-rwxr-xr-x  1 deepthought  deepthought    978 Jan 19 16:28 ft_putchar.c
-rwxr-xr-x  1 deepthought  deepthought    990 Jan 19 16:28 ft_putchar_fd.c
-rwxr-xr-x  1 deepthought  deepthought   1059 Jan 19 16:28 ft_putendl.c
-rwxr-xr-x  1 deepthought  deepthought   1006 Jan 19 16:28 ft_putendl_fd.c
-rwxr-xr-x  1 deepthought  deepthought   1151 Jan 19 16:28 ft_putnbr.c
-rwxr-xr-x  1 deepthought  deepthought   1204 Jan 19 16:28 ft_putnbr_fd.c
-rwxr-xr-x  1 deepthought  deepthought   1018 Jan 19 16:28 ft_putstr.c
-rwxr-xr-x  1 deepthought  deepthought   1006 Jan 19 16:28 ft_putstr_fd.c
-rw-r--r--  1 deepthought  deepthought   1118 Jan 19 16:28 ft_range.c
-rwxr-xr-x  1 deepthought  deepthought   1113 Jan 19 16:28 ft_strcat.c
-rwxr-xr-x  1 deepthought  deepthought   1056 Jan 19 16:28 ft_strchr.c
-rwxr-xr-x  1 deepthought  deepthought   1042 Jan 19 16:28 ft_strclr.c
-rwxr-xr-x  1 deepthought  deepthought   1099 Jan 19 16:28 ft_strcmp.c
-rwxr-xr-x  1 deepthought  deepthought   1068 Jan 19 16:28 ft_strcpy.c
-rwxr-xr-x  1 deepthought  deepthought    992 Jan 19 16:28 ft_strdel.c
-rwxr-xr-x  1 deepthought  deepthought   1090 Jan 19 16:28 ft_strdup.c
-rwxr-xr-x  1 deepthought  deepthought   1139 Jan 19 16:28 ft_strequ.c
-rwxr-xr-x  1 deepthought  deepthought   1049 Jan 19 16:28 ft_striter.c
-rwxr-xr-x  1 deepthought  deepthought   1067 Jan 19 16:28 ft_striteri.c
-rwxr-xr-x  1 deepthought  deepthought   1267 Jan 19 16:28 ft_strjoin.c
-rw-r--r--  1 deepthought  deepthought   1312 Jan 19 16:28 ft_strlcat.c
-rwxr-xr-x  1 deepthought  deepthought   1050 Jan 19 16:28 ft_strlen.c
-rwxr-xr-x  1 deepthought  deepthought   1237 Jan 19 16:28 ft_strmap.c
-rwxr-xr-x  1 deepthought  deepthought   1182 Jan 19 16:28 ft_strmapi.c
-rwxr-xr-x  1 deepthought  deepthought   1136 Jan 19 16:28 ft_strncat.c
-rwxr-xr-x  1 deepthought  deepthought   1201 Jan 19 16:28 ft_strncmp.c
-rwxr-xr-x  1 deepthought  deepthought   1122 Jan 19 16:28 ft_strncpy.c
-rwxr-xr-x  1 deepthought  deepthought   1147 Jan 19 16:28 ft_strnequ.c
-rwxr-xr-x  1 deepthought  deepthought   1083 Jan 19 16:28 ft_strnew.c
-rwxr-xr-x  1 deepthought  deepthought   1234 Jan 19 16:28 ft_strnstr.c
-rwxr-xr-x  1 deepthought  deepthought   1122 Jan 19 16:28 ft_strrchr.c
-rwxr-xr-x  1 deepthought  deepthought   1766 Jan 19 16:28 ft_strsplit.c
-rwxr-xr-x  1 deepthought  deepthought   1268 Jan 19 16:28 ft_strstr.c
-rwxr-xr-x  1 deepthought  deepthought   1251 Jan 19 16:28 ft_strsub.c
-rwxr-xr-x  1 deepthought  deepthought   1336 Jan 19 16:28 ft_strtrim.c
-rwxr-xr-x  1 deepthought  deepthought    997 Jan 19 16:28 ft_tolower.c
-rwxr-xr-x  1 deepthought  deepthought    997 Jan 19 16:28 ft_toupper.c
-rw-r--r--  1 deepthought  deepthought   1003 Jan 19 16:28 ft_ultimate_div_mod.c
-rw-r--r--  1 deepthought  deepthought   1152 Jan 19 16:28 ft_ultimate_range.c
-rwxr-xr-x  1 deepthought  deepthought   4009 Jan 19 16:28 libft.h

= libft_basics_1 ===============================================================
total 520
-rwxr-xr-x  1 deepthought  deepthought  1102 Jan 19 16:28 Makefile
-rwxr-xr-x  1 deepthought  deepthought  1406 Jan 19 16:28 ft_atoi.c
-rwxr-xr-x  1 deepthought  deepthought   973 Jan 19 16:28 ft_bzero.c
-rw-r--r--  1 deepthought  deepthought  1017 Jan 19 16:28 ft_div_mod.c
-rwxr-xr-x  1 deepthought  deepthought  1012 Jan 19 16:28 ft_isalnum.c
-rwxr-xr-x  1 deepthought  deepthought  1021 Jan 19 16:28 ft_isalpha.c
-rwxr-xr-x  1 deepthought  deepthought   990 Jan 19 16:28 ft_isascii.c
-rwxr-xr-x  1 deepthought  deepthought   992 Jan 19 16:28 ft_isdigit.c
-rwxr-xr-x  1 deepthought  deepthought   991 Jan 19 16:28 ft_isprint.c
-rwxr-xr-x  1 deepthought  deepthought  1328 Jan 19 16:28 ft_itoa.c
-rwxr-xr-x  1 deepthought  deepthought   993 Jan 19 16:28 ft_lstadd.c
-rwxr-xr-x  1 deepthought  deepthought  1059 Jan 19 16:28 ft_lstdel.c
-rwxr-xr-x  1 deepthought  deepthought  1054 Jan 19 16:28 ft_lstdelone.c
-rwxr-xr-x  1 deepthought  deepthought  1045 Jan 19 16:28 ft_lstiter.c
-rwxr-xr-x  1 deepthought  deepthought  1219 Jan 19 16:28 ft_lstmap.c
-rwxr-xr-x  1 deepthought  deepthought  1330 Jan 19 16:28 ft_lstnew.c
-rwxr-xr-x  1 deepthought  deepthought  1051 Jan 19 16:28 ft_memalloc.c
-rwxr-xr-x  1 deepthought  deepthought  1222 Jan 19 16:28 ft_memccpy.c
-rwxr-xr-x  1 deepthought  deepthought  1133 Jan 19 16:28 ft_memchr.c
-rwxr-xr-x  1 deepthought  deepthought  1227 Jan 19 16:28 ft_memcmp.c
-rwxr-xr-x  1 deepthought  deepthought  1142 Jan 19 16:28 ft_memcpy.c
-rwxr-xr-x  1 deepthought  deepthought   991 Jan 19 16:28 ft_memdel.c
-rwxr-xr-x  1 deepthought  deepthought  1155 Jan 19 16:28 ft_memmove.c
-rwxr-xr-x  1 deepthought  deepthought  1123 Jan 19 16:28 ft_memset.c
-rw-r--r--  1 deepthought  deepthought  1126 Jan 19 16:28 ft_printmatrice.c
-rwxr-xr-x  1 deepthought  deepthought   978 Jan 19 16:28 ft_putchar.c
-rwxr-xr-x  1 deepthought  deepthought   990 Jan 19 16:28 ft_putchar_fd.c
-rwxr-xr-x  1 deepthought  deepthought  1059 Jan 19 16:28 ft_putendl.c
-rwxr-xr-x  1 deepthought  deepthought  1006 Jan 19 16:28 ft_putendl_fd.c
-rwxr-xr-x  1 deepthought  deepthought  1151 Jan 19 16:28 ft_putnbr.c
-rwxr-xr-x  1 deepthought  deepthought  1204 Jan 19 16:28 ft_putnbr_fd.c
-rwxr-xr-x  1 deepthought  deepthought  1018 Jan 19 16:28 ft_putstr.c
-rwxr-xr-x  1 deepthought  deepthought  1006 Jan 19 16:28 ft_putstr_fd.c
-rw-r--r--  1 deepthought  deepthought  1118 Jan 19 16:28 ft_range.c
-rwxr-xr-x  1 deepthought  deepthought  1113 Jan 19 16:28 ft_strcat.c
-rwxr-xr-x  1 deepthought  deepthought  1056 Jan 19 16:28 ft_strchr.c
-rwxr-xr-x  1 deepthought  deepthought  1042 Jan 19 16:28 ft_strclr.c
-rwxr-xr-x  1 deepthought  deepthought  1099 Jan 19 16:28 ft_strcmp.c
-rwxr-xr-x  1 deepthought  deepthought  1068 Jan 19 16:28 ft_strcpy.c
-rwxr-xr-x  1 deepthought  deepthought   992 Jan 19 16:28 ft_strdel.c
-rwxr-xr-x  1 deepthought  deepthought  1090 Jan 19 16:28 ft_strdup.c
-rwxr-xr-x  1 deepthought  deepthought  1139 Jan 19 16:28 ft_strequ.c
-rwxr-xr-x  1 deepthought  deepthought  1049 Jan 19 16:28 ft_striter.c
-rwxr-xr-x  1 deepthought  deepthought  1067 Jan 19 16:28 ft_striteri.c
-rwxr-xr-x  1 deepthought  deepthought  1267 Jan 19 16:28 ft_strjoin.c
-rw-r--r--  1 deepthought  deepthought  1312 Jan 19 16:28 ft_strlcat.c
-rwxr-xr-x  1 deepthought  deepthought  1050 Jan 19 16:28 ft_strlen.c
-rwxr-xr-x  1 deepthought  deepthought  1237 Jan 19 16:28 ft_strmap.c
-rwxr-xr-x  1 deepthought  deepthought  1182 Jan 19 16:28 ft_strmapi.c
-rwxr-xr-x  1 deepthought  deepthought  1136 Jan 19 16:28 ft_strncat.c
-rwxr-xr-x  1 deepthought  deepthought  1201 Jan 19 16:28 ft_strncmp.c
-rwxr-xr-x  1 deepthought  deepthought  1122 Jan 19 16:28 ft_strncpy.c
-rwxr-xr-x  1 deepthought  deepthought  1147 Jan 19 16:28 ft_strnequ.c
-rwxr-xr-x  1 deepthought  deepthought  1083 Jan 19 16:28 ft_strnew.c
-rwxr-xr-x  1 deepthought  deepthought  1234 Jan 19 16:28 ft_strnstr.c
-rwxr-xr-x  1 deepthought  deepthought  1122 Jan 19 16:28 ft_strrchr.c
-rwxr-xr-x  1 deepthought  deepthought  1766 Jan 19 16:28 ft_strsplit.c
-rwxr-xr-x  1 deepthought  deepthought  1268 Jan 19 16:28 ft_strstr.c
-rwxr-xr-x  1 deepthought  deepthought  1251 Jan 19 16:28 ft_strsub.c
-rwxr-xr-x  1 deepthought  deepthought  1336 Jan 19 16:28 ft_strtrim.c
-rwxr-xr-x  1 deepthought  deepthought   997 Jan 19 16:28 ft_tolower.c
-rwxr-xr-x  1 deepthought  deepthought   997 Jan 19 16:28 ft_toupper.c
-rw-r--r--  1 deepthought  deepthought  1003 Jan 19 16:28 ft_ultimate_div_mod.c
-rw-r--r--  1 deepthought  deepthought  1152 Jan 19 16:28 ft_ultimate_range.c
-rwxr-xr-x  1 deepthought  deepthought  4009 Jan 19 16:28 libft.h

rm -f *.o

cc -Wall -Wextra -Werror -I. -c *.c
ar rc libft.a *.o
ranlib libft.a

rm -f *.o
rm -f libft.a

cc -Wall -Wextra -Werror -I. -c *.c
ar rc libft.a *.o
ranlib libft.a

rm -f *.o
rm -f libft.a
cc -Wall -Wextra -Werror -I. -c *.c
ar rc libft.a *.o
ranlib libft.a

-rw-r--r--  1 deepthought  deepthought  56224 Jan 19 16:28 libft.a

gcc -Wall -Wextra -Werror -g3   -c -o test_ft_atoi.o test_ft_atoi.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_bzero.o test_ft_bzero.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_isalnum.o test_ft_isalnum.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_isalpha.o test_ft_isalpha.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_isascii.o test_ft_isascii.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_isdigit.o test_ft_isdigit.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_isprint.o test_ft_isprint.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_memccpy.o test_ft_memccpy.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_memchr.o test_ft_memchr.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_memcmp.o test_ft_memcmp.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_memcpy.o test_ft_memcpy.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_memmove.o test_ft_memmove.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_memset.o test_ft_memset.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_strcat.o test_ft_strcat.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_strchr.o test_ft_strchr.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_strcmp.o test_ft_strcmp.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_strcpy.o test_ft_strcpy.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_strdup.o test_ft_strdup.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_strlcat.o test_ft_strlcat.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_strlen.o test_ft_strlen.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_strncat.o test_ft_strncat.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_strncmp.o test_ft_strncmp.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_strncpy.o test_ft_strncpy.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_strnstr.o test_ft_strnstr.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_strrchr.o test_ft_strrchr.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_strstr.o test_ft_strstr.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_tolower.o test_ft_tolower.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_toupper.o test_ft_toupper.c
gcc -Wall -Wextra -Werror -g3   -c -o main.o main.c
gcc -Wall -Wextra -Werror -g3 -o test_lib -L. -lft test_ft_atoi.o test_ft_bzero.o test_ft_isalnum.o test_ft_isalpha.o test_ft_isascii.o test_ft_isdigit.o test_ft_isprint.o test_ft_memccpy.o test_ft_memchr.o test_ft_memcmp.o test_ft_memcpy.o test_ft_memmove.o test_ft_memset.o test_ft_strcat.o test_ft_strchr.o test_ft_strcmp.o test_ft_strcpy.o test_ft_strdup.o test_ft_strlcat.o test_ft_strlen.o test_ft_strncat.o test_ft_strncmp.o test_ft_strncpy.o test_ft_strnstr.o test_ft_strrchr.o test_ft_strstr.o test_ft_tolower.o test_ft_toupper.o main.o

Testing ft_atoi
 [*] ft_atoi : [ok]
Testing ft_bzero
 [*] ft_bzero : [ok]
Testing ft_isalnum
 [*] ft_isalnum : [ok]
Testing ft_isalpha
 [*] ft_isalpha : [ok]
Testing ft_isascii
 [*] ft_isascii : [ok]
Testing ft_isdigit
 [*] ft_isdigit : [ok]
Testing ft_isprint
 [*] ft_isprint : [ok]
Testing ft_memccpy
 [*] ft_memccpy : [ok]
Testing ft_memchr
 [*] ft_memchr : [ok]
Testing ft_memcmp
 [*] ft_memcmp : [ok]
Testing ft_memcpy
 [*] ft_memcpy : [ok]
Testing ft_memmove
 [*] ft_memmove : [ok]
Testing ft_memset
 [*] ft_memset : [ok]
Testing ft_strcat
 [*] ft_strcat : [ok]
Testing ft_strchr
 [*] ft_strchr : [ok]
Testing ft_strcmp
 [*] ft_strcmp : [ok]
Testing ft_strcpy
 [*] ft_strcpy : [ok]
Testing ft_strdup
 [*] ft_strdup : [ok]
Testing ft_strlcat
 [*] ft_strlcat : [ok]
Testing ft_strlen
 [*] ft_strlen : [ok]
Testing ft_strncat
 [*] ft_strncat : [ok]
Testing ft_strncmp
 [*] ft_strncmp : [ok]
Testing ft_atoi
 [*] ft_atoi : [ok]
Testing ft_strnstr
 [*] ft_strnstr : [ok]
Testing ft_strrchr
 [*] ft_strrchr : [ok]
Testing ft_strstr
 [*] ft_strstr : [ok]
Testing ft_tolower
 [*] ft_tolower : [ok]
Testing ft_toupper
 [*] ft_toupper : [ok]

28/28 correct functions
Grade: 60

= libft_basics_2 ===============================================================
total 520
-rwxr-xr-x  1 deepthought  deepthought  1102 Jan 19 16:28 Makefile
-rwxr-xr-x  1 deepthought  deepthought  1406 Jan 19 16:28 ft_atoi.c
-rwxr-xr-x  1 deepthought  deepthought   973 Jan 19 16:28 ft_bzero.c
-rw-r--r--  1 deepthought  deepthought  1017 Jan 19 16:28 ft_div_mod.c
-rwxr-xr-x  1 deepthought  deepthought  1012 Jan 19 16:28 ft_isalnum.c
-rwxr-xr-x  1 deepthought  deepthought  1021 Jan 19 16:28 ft_isalpha.c
-rwxr-xr-x  1 deepthought  deepthought   990 Jan 19 16:28 ft_isascii.c
-rwxr-xr-x  1 deepthought  deepthought   992 Jan 19 16:28 ft_isdigit.c
-rwxr-xr-x  1 deepthought  deepthought   991 Jan 19 16:28 ft_isprint.c
-rwxr-xr-x  1 deepthought  deepthought  1328 Jan 19 16:28 ft_itoa.c
-rwxr-xr-x  1 deepthought  deepthought   993 Jan 19 16:28 ft_lstadd.c
-rwxr-xr-x  1 deepthought  deepthought  1059 Jan 19 16:28 ft_lstdel.c
-rwxr-xr-x  1 deepthought  deepthought  1054 Jan 19 16:28 ft_lstdelone.c
-rwxr-xr-x  1 deepthought  deepthought  1045 Jan 19 16:28 ft_lstiter.c
-rwxr-xr-x  1 deepthought  deepthought  1219 Jan 19 16:28 ft_lstmap.c
-rwxr-xr-x  1 deepthought  deepthought  1330 Jan 19 16:28 ft_lstnew.c
-rwxr-xr-x  1 deepthought  deepthought  1051 Jan 19 16:28 ft_memalloc.c
-rwxr-xr-x  1 deepthought  deepthought  1222 Jan 19 16:28 ft_memccpy.c
-rwxr-xr-x  1 deepthought  deepthought  1133 Jan 19 16:28 ft_memchr.c
-rwxr-xr-x  1 deepthought  deepthought  1227 Jan 19 16:28 ft_memcmp.c
-rwxr-xr-x  1 deepthought  deepthought  1142 Jan 19 16:28 ft_memcpy.c
-rwxr-xr-x  1 deepthought  deepthought   991 Jan 19 16:28 ft_memdel.c
-rwxr-xr-x  1 deepthought  deepthought  1155 Jan 19 16:28 ft_memmove.c
-rwxr-xr-x  1 deepthought  deepthought  1123 Jan 19 16:28 ft_memset.c
-rw-r--r--  1 deepthought  deepthought  1126 Jan 19 16:28 ft_printmatrice.c
-rwxr-xr-x  1 deepthought  deepthought   978 Jan 19 16:28 ft_putchar.c
-rwxr-xr-x  1 deepthought  deepthought   990 Jan 19 16:28 ft_putchar_fd.c
-rwxr-xr-x  1 deepthought  deepthought  1059 Jan 19 16:28 ft_putendl.c
-rwxr-xr-x  1 deepthought  deepthought  1006 Jan 19 16:28 ft_putendl_fd.c
-rwxr-xr-x  1 deepthought  deepthought  1151 Jan 19 16:28 ft_putnbr.c
-rwxr-xr-x  1 deepthought  deepthought  1204 Jan 19 16:28 ft_putnbr_fd.c
-rwxr-xr-x  1 deepthought  deepthought  1018 Jan 19 16:28 ft_putstr.c
-rwxr-xr-x  1 deepthought  deepthought  1006 Jan 19 16:28 ft_putstr_fd.c
-rw-r--r--  1 deepthought  deepthought  1118 Jan 19 16:28 ft_range.c
-rwxr-xr-x  1 deepthought  deepthought  1113 Jan 19 16:28 ft_strcat.c
-rwxr-xr-x  1 deepthought  deepthought  1056 Jan 19 16:28 ft_strchr.c
-rwxr-xr-x  1 deepthought  deepthought  1042 Jan 19 16:28 ft_strclr.c
-rwxr-xr-x  1 deepthought  deepthought  1099 Jan 19 16:28 ft_strcmp.c
-rwxr-xr-x  1 deepthought  deepthought  1068 Jan 19 16:28 ft_strcpy.c
-rwxr-xr-x  1 deepthought  deepthought   992 Jan 19 16:28 ft_strdel.c
-rwxr-xr-x  1 deepthought  deepthought  1090 Jan 19 16:28 ft_strdup.c
-rwxr-xr-x  1 deepthought  deepthought  1139 Jan 19 16:28 ft_strequ.c
-rwxr-xr-x  1 deepthought  deepthought  1049 Jan 19 16:28 ft_striter.c
-rwxr-xr-x  1 deepthought  deepthought  1067 Jan 19 16:28 ft_striteri.c
-rwxr-xr-x  1 deepthought  deepthought  1267 Jan 19 16:28 ft_strjoin.c
-rw-r--r--  1 deepthought  deepthought  1312 Jan 19 16:28 ft_strlcat.c
-rwxr-xr-x  1 deepthought  deepthought  1050 Jan 19 16:28 ft_strlen.c
-rwxr-xr-x  1 deepthought  deepthought  1237 Jan 19 16:28 ft_strmap.c
-rwxr-xr-x  1 deepthought  deepthought  1182 Jan 19 16:28 ft_strmapi.c
-rwxr-xr-x  1 deepthought  deepthought  1136 Jan 19 16:28 ft_strncat.c
-rwxr-xr-x  1 deepthought  deepthought  1201 Jan 19 16:28 ft_strncmp.c
-rwxr-xr-x  1 deepthought  deepthought  1122 Jan 19 16:28 ft_strncpy.c
-rwxr-xr-x  1 deepthought  deepthought  1147 Jan 19 16:28 ft_strnequ.c
-rwxr-xr-x  1 deepthought  deepthought  1083 Jan 19 16:28 ft_strnew.c
-rwxr-xr-x  1 deepthought  deepthought  1234 Jan 19 16:28 ft_strnstr.c
-rwxr-xr-x  1 deepthought  deepthought  1122 Jan 19 16:28 ft_strrchr.c
-rwxr-xr-x  1 deepthought  deepthought  1766 Jan 19 16:28 ft_strsplit.c
-rwxr-xr-x  1 deepthought  deepthought  1268 Jan 19 16:28 ft_strstr.c
-rwxr-xr-x  1 deepthought  deepthought  1251 Jan 19 16:28 ft_strsub.c
-rwxr-xr-x  1 deepthought  deepthought  1336 Jan 19 16:28 ft_strtrim.c
-rwxr-xr-x  1 deepthought  deepthought   997 Jan 19 16:28 ft_tolower.c
-rwxr-xr-x  1 deepthought  deepthought   997 Jan 19 16:28 ft_toupper.c
-rw-r--r--  1 deepthought  deepthought  1003 Jan 19 16:28 ft_ultimate_div_mod.c
-rw-r--r--  1 deepthought  deepthought  1152 Jan 19 16:28 ft_ultimate_range.c
-rwxr-xr-x  1 deepthought  deepthought  4009 Jan 19 16:28 libft.h

rm -f *.o

cc -Wall -Wextra -Werror -I. -c *.c
ar rc libft.a *.o
ranlib libft.a

rm -f *.o
rm -f libft.a

cc -Wall -Wextra -Werror -I. -c *.c
ar rc libft.a *.o
ranlib libft.a

rm -f *.o
rm -f libft.a
cc -Wall -Wextra -Werror -I. -c *.c
ar rc libft.a *.o
ranlib libft.a

-rw-r--r--  1 deepthought  deepthought  56224 Jan 19 16:28 libft.a

gcc -Wall -Wextra -Werror -g3   -c -o test_ft_strnew.o test_ft_strnew.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_strdel.o test_ft_strdel.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_strclr.o test_ft_strclr.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_striter.o test_ft_striter.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_striteri.o test_ft_striteri.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_strmap.o test_ft_strmap.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_strmapi.o test_ft_strmapi.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_strequ.o test_ft_strequ.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_strnequ.o test_ft_strnequ.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_strsub.o test_ft_strsub.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_strjoin.o test_ft_strjoin.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_strtrim.o test_ft_strtrim.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_strsplit.o test_ft_strsplit.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_itoa.o test_ft_itoa.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_putstr.o test_ft_putstr.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_putchar.o test_ft_putchar.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_putendl.o test_ft_putendl.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_putnbr.o test_ft_putnbr.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_putchar_fd.o test_ft_putchar_fd.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_putendl_fd.o test_ft_putendl_fd.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_putnbr_fd.o test_ft_putnbr_fd.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_putstr_fd.o test_ft_putstr_fd.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_memalloc.o test_ft_memalloc.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_memdel.o test_ft_memdel.c
gcc -Wall -Wextra -Werror -g3   -c -o main.o main.c
gcc -Wall -Wextra -Werror -g3 -o test_lib -L. -lft test_ft_strnew.o test_ft_strdel.o test_ft_strclr.o test_ft_striter.o test_ft_striteri.o test_ft_strmap.o test_ft_strmapi.o test_ft_strequ.o test_ft_strnequ.o test_ft_strsub.o test_ft_strjoin.o test_ft_strtrim.o test_ft_strsplit.o test_ft_itoa.o test_ft_putstr.o test_ft_putchar.o test_ft_putendl.o test_ft_putnbr.o test_ft_putchar_fd.o test_ft_putendl_fd.o test_ft_putnbr_fd.o test_ft_putstr_fd.o test_ft_memalloc.o test_ft_memdel.o main.o

Testing ft_memalloc
 [*] ft_memalloc : [ok]
Testing ft_memdel
 [*] ft_memdel : [ok]
Testing ft_strnew
 [*] ft_strnew : [ok]
Testing ft_strdel
 [*] ft_strdel : [ok]
Testing ft_strclr
 [*] ft_strclr : [ok]
Testing ft_striter
 [*] ft_striter : [ok]
Testing ft_striteri
 [*] ft_striteri : [ok]
Testing ft_strmap
 [*] ft_strmap : [ok]
Testing ft_strmapi
 [*] ft_strmapi : [ok]
Testing ft_strequ
 [*] ft_strequ : [ok]
Testing ft_strnequ
 [*] ft_strnequ : [ok]
Testing ft_strsub
 [*] ft_strsub : [ok]
Testing ft_strjoin
 [*] ft_strjoin : [ok]
Testing ft_strtrim
 [*] ft_strtrim : [ok]
Testing ft_strsplit
 [*] ft_strsplit : [ok]
Testing ft_itoa
 [*] ft_itoa : [ok]
Testing ft_putchar
 [*] ft_putchar : [ok]
Testing ft_putstr
 [*] ft_putstr : [ok]
Testing ft_putendl
 [*] ft_putendl : [ok]
Testing ft_putnbr
 [*] ft_putnbr : [ok]
Testing ft_putchar_fd
 [*] ft_putchar_fd : [ok]
Testing ft_putstr_fd
 [*] ft_putstr_fd : [ok]
Testing ft_putendl_fd
 [*] ft_putendl_fd : [ok]
Testing ft_putnbr_fd
 [*] ft_putnbr_fd : [ok]

24/24 correct functions
Grade: 40

= libft_bonus ==================================================================
total 520
-rwxr-xr-x  1 deepthought  deepthought  1102 Jan 19 16:28 Makefile
-rwxr-xr-x  1 deepthought  deepthought  1406 Jan 19 16:28 ft_atoi.c
-rwxr-xr-x  1 deepthought  deepthought   973 Jan 19 16:28 ft_bzero.c
-rw-r--r--  1 deepthought  deepthought  1017 Jan 19 16:28 ft_div_mod.c
-rwxr-xr-x  1 deepthought  deepthought  1012 Jan 19 16:28 ft_isalnum.c
-rwxr-xr-x  1 deepthought  deepthought  1021 Jan 19 16:28 ft_isalpha.c
-rwxr-xr-x  1 deepthought  deepthought   990 Jan 19 16:28 ft_isascii.c
-rwxr-xr-x  1 deepthought  deepthought   992 Jan 19 16:28 ft_isdigit.c
-rwxr-xr-x  1 deepthought  deepthought   991 Jan 19 16:28 ft_isprint.c
-rwxr-xr-x  1 deepthought  deepthought  1328 Jan 19 16:28 ft_itoa.c
-rwxr-xr-x  1 deepthought  deepthought   993 Jan 19 16:28 ft_lstadd.c
-rwxr-xr-x  1 deepthought  deepthought  1059 Jan 19 16:28 ft_lstdel.c
-rwxr-xr-x  1 deepthought  deepthought  1054 Jan 19 16:28 ft_lstdelone.c
-rwxr-xr-x  1 deepthought  deepthought  1045 Jan 19 16:28 ft_lstiter.c
-rwxr-xr-x  1 deepthought  deepthought  1219 Jan 19 16:28 ft_lstmap.c
-rwxr-xr-x  1 deepthought  deepthought  1330 Jan 19 16:28 ft_lstnew.c
-rwxr-xr-x  1 deepthought  deepthought  1051 Jan 19 16:28 ft_memalloc.c
-rwxr-xr-x  1 deepthought  deepthought  1222 Jan 19 16:28 ft_memccpy.c
-rwxr-xr-x  1 deepthought  deepthought  1133 Jan 19 16:28 ft_memchr.c
-rwxr-xr-x  1 deepthought  deepthought  1227 Jan 19 16:28 ft_memcmp.c
-rwxr-xr-x  1 deepthought  deepthought  1142 Jan 19 16:28 ft_memcpy.c
-rwxr-xr-x  1 deepthought  deepthought   991 Jan 19 16:28 ft_memdel.c
-rwxr-xr-x  1 deepthought  deepthought  1155 Jan 19 16:28 ft_memmove.c
-rwxr-xr-x  1 deepthought  deepthought  1123 Jan 19 16:28 ft_memset.c
-rw-r--r--  1 deepthought  deepthought  1126 Jan 19 16:28 ft_printmatrice.c
-rwxr-xr-x  1 deepthought  deepthought   978 Jan 19 16:28 ft_putchar.c
-rwxr-xr-x  1 deepthought  deepthought   990 Jan 19 16:28 ft_putchar_fd.c
-rwxr-xr-x  1 deepthought  deepthought  1059 Jan 19 16:28 ft_putendl.c
-rwxr-xr-x  1 deepthought  deepthought  1006 Jan 19 16:28 ft_putendl_fd.c
-rwxr-xr-x  1 deepthought  deepthought  1151 Jan 19 16:28 ft_putnbr.c
-rwxr-xr-x  1 deepthought  deepthought  1204 Jan 19 16:28 ft_putnbr_fd.c
-rwxr-xr-x  1 deepthought  deepthought  1018 Jan 19 16:28 ft_putstr.c
-rwxr-xr-x  1 deepthought  deepthought  1006 Jan 19 16:28 ft_putstr_fd.c
-rw-r--r--  1 deepthought  deepthought  1118 Jan 19 16:28 ft_range.c
-rwxr-xr-x  1 deepthought  deepthought  1113 Jan 19 16:28 ft_strcat.c
-rwxr-xr-x  1 deepthought  deepthought  1056 Jan 19 16:28 ft_strchr.c
-rwxr-xr-x  1 deepthought  deepthought  1042 Jan 19 16:28 ft_strclr.c
-rwxr-xr-x  1 deepthought  deepthought  1099 Jan 19 16:28 ft_strcmp.c
-rwxr-xr-x  1 deepthought  deepthought  1068 Jan 19 16:28 ft_strcpy.c
-rwxr-xr-x  1 deepthought  deepthought   992 Jan 19 16:28 ft_strdel.c
-rwxr-xr-x  1 deepthought  deepthought  1090 Jan 19 16:28 ft_strdup.c
-rwxr-xr-x  1 deepthought  deepthought  1139 Jan 19 16:28 ft_strequ.c
-rwxr-xr-x  1 deepthought  deepthought  1049 Jan 19 16:28 ft_striter.c
-rwxr-xr-x  1 deepthought  deepthought  1067 Jan 19 16:28 ft_striteri.c
-rwxr-xr-x  1 deepthought  deepthought  1267 Jan 19 16:28 ft_strjoin.c
-rw-r--r--  1 deepthought  deepthought  1312 Jan 19 16:28 ft_strlcat.c
-rwxr-xr-x  1 deepthought  deepthought  1050 Jan 19 16:28 ft_strlen.c
-rwxr-xr-x  1 deepthought  deepthought  1237 Jan 19 16:28 ft_strmap.c
-rwxr-xr-x  1 deepthought  deepthought  1182 Jan 19 16:28 ft_strmapi.c
-rwxr-xr-x  1 deepthought  deepthought  1136 Jan 19 16:28 ft_strncat.c
-rwxr-xr-x  1 deepthought  deepthought  1201 Jan 19 16:28 ft_strncmp.c
-rwxr-xr-x  1 deepthought  deepthought  1122 Jan 19 16:28 ft_strncpy.c
-rwxr-xr-x  1 deepthought  deepthought  1147 Jan 19 16:28 ft_strnequ.c
-rwxr-xr-x  1 deepthought  deepthought  1083 Jan 19 16:28 ft_strnew.c
-rwxr-xr-x  1 deepthought  deepthought  1234 Jan 19 16:28 ft_strnstr.c
-rwxr-xr-x  1 deepthought  deepthought  1122 Jan 19 16:28 ft_strrchr.c
-rwxr-xr-x  1 deepthought  deepthought  1766 Jan 19 16:28 ft_strsplit.c
-rwxr-xr-x  1 deepthought  deepthought  1268 Jan 19 16:28 ft_strstr.c
-rwxr-xr-x  1 deepthought  deepthought  1251 Jan 19 16:28 ft_strsub.c
-rwxr-xr-x  1 deepthought  deepthought  1336 Jan 19 16:28 ft_strtrim.c
-rwxr-xr-x  1 deepthought  deepthought   997 Jan 19 16:28 ft_tolower.c
-rwxr-xr-x  1 deepthought  deepthought   997 Jan 19 16:28 ft_toupper.c
-rw-r--r--  1 deepthought  deepthought  1003 Jan 19 16:28 ft_ultimate_div_mod.c
-rw-r--r--  1 deepthought  deepthought  1152 Jan 19 16:28 ft_ultimate_range.c
-rwxr-xr-x  1 deepthought  deepthought  4009 Jan 19 16:28 libft.h

rm -f *.o

cc -Wall -Wextra -Werror -I. -c *.c
ar rc libft.a *.o
ranlib libft.a

rm -f *.o
rm -f libft.a

cc -Wall -Wextra -Werror -I. -c *.c
ar rc libft.a *.o
ranlib libft.a

rm -f *.o
rm -f libft.a
cc -Wall -Wextra -Werror -I. -c *.c
ar rc libft.a *.o
ranlib libft.a

-rw-r--r--  1 deepthought  deepthought  56224 Jan 19 16:28 libft.a

gcc -Wall -Wextra -Werror -g3   -c -o test_ft_lstadd.o test_ft_lstadd.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_lstdel.o test_ft_lstdel.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_lstdelone.o test_ft_lstdelone.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_lstiter.o test_ft_lstiter.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_lstmap.o test_ft_lstmap.c
gcc -Wall -Wextra -Werror -g3   -c -o test_ft_lstnew.o test_ft_lstnew.c
gcc -Wall -Wextra -Werror -g3   -c -o main.o main.c
gcc -Wall -Wextra -Werror -g3 -o test_lib -L. -lft test_ft_lstadd.o test_ft_lstdel.o test_ft_lstdelone.o test_ft_lstiter.o test_ft_lstmap.o test_ft_lstnew.o main.o

Testing ft_lstadd
 [*] Using ft_lstadd(&list2, list) where both list are zeroed t_list structs
 [*] ft_lstadd : [ok]
Testing ft_lstdel
 [*] Applying a function that zeroes an int-size memory chunk before delete
 [*] ft_lstdel : [ok]
Testing ft_lstdelone
 [*] Applying a function that zeroes an int-size memory chunk before delete
 [*] ft_lstdelone : [ok]
Testing ft_lstiter
 [*] Applying a function that set content_size to 42 on each links
 [*] ft_lstiter : [ok]
Testing ft_lstmap
 [*] Applying a function that doubles content_size and set strings in content to Uppercase
 [*] ft_lstmap : [ok]
Testing ft_lstnew
 [*] ft_lstnew : [ok]

6/6 correct functions
Grade: 25

= Final grade: 125 =============================================================
