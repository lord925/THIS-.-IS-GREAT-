{\rtf1\ansi\ansicpg1252\cocoartf1561\cocoasubrtf600
{\fonttbl\f0\fswiss\fcharset0 Helvetica;\f1\fnil\fcharset0 Menlo-Regular;\f2\fnil\fcharset0 Menlo-Italic;
\f3\fnil\fcharset0 Menlo-BoldItalic;}
{\colortbl;\red255\green255\blue255;\red109\green109\blue109;\red32\green32\blue32;\red191\green100\blue38;
\red153\green168\blue186;\red86\green132\blue173;\red88\green118\blue71;\red81\green136\blue67;}
{\*\expandedcolortbl;;\csgenericrgb\c42745\c42745\c42745;\csgenericrgb\c12549\c12549\c12549;\csgenericrgb\c74902\c39216\c14902;
\csgenericrgb\c60000\c65882\c72941;\csgenericrgb\c33725\c51765\c67843;\csgenericrgb\c34510\c46275\c27843;\csgenericrgb\c31765\c53333\c26275;}
\margl1440\margr1440\vieww10800\viewh8400\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 \
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f1 \cf2 \cb3 //\
// Source code recreated from a .class file by IntelliJ IDEA\
// (powered by Fernflower decompiler)\
//\
\
\cf4 package \cf5 sun.security.pkcs11\cf4 ;\
\
import \cf5 java.io.File\cf4 ;\
import \cf5 java.io.IOException\cf4 ;\
import \cf5 java.io.InputStream\cf4 ;\
import \cf5 java.io.NotSerializableException\cf4 ;\
import \cf5 java.io.ObjectStreamException\cf4 ;\
import \cf5 java.io.Serializable\cf4 ;\
import \cf5 java.security.AccessController\cf4 ;\
import \cf5 java.security.AuthProvider\cf4 ;\
import \cf5 java.security.InvalidParameterException\cf4 ;\
import \cf5 java.security.Key\cf4 ;\
import \cf5 java.security.NoSuchAlgorithmException\cf4 ;\
import \cf5 java.security.PrivilegedAction\cf4 ;\
import \cf5 java.security.PrivilegedActionException\cf4 ;\
import \cf5 java.security.PrivilegedExceptionAction\cf4 ;\
import \cf5 java.security.ProviderException\cf4 ;\
import \cf5 java.security.Security\cf4 ;\
import \cf5 java.security.SecurityPermission\cf4 ;\
import \cf5 java.security.Provider.Service\cf4 ;\
import \cf5 java.security.interfaces.DSAPrivateKey\cf4 ;\
import \cf5 java.security.interfaces.DSAPublicKey\cf4 ;\
import \cf5 java.security.interfaces.ECPrivateKey\cf4 ;\
import \cf5 java.security.interfaces.ECPublicKey\cf4 ;\
import \cf5 java.security.interfaces.RSAPrivateKey\cf4 ;\
import \cf5 java.security.interfaces.RSAPublicKey\cf4 ;\
import \cf5 java.text.MessageFormat\cf4 ;\
import \cf5 java.util.ArrayList\cf4 ;\
import \cf5 java.util.Arrays\cf4 ;\
import \cf5 java.util.HashMap\cf4 ;\
import \cf5 java.util.Iterator\cf4 ;\
import \cf5 java.util.List\cf4 ;\
import \cf5 java.util.Map\cf4 ;\
import \cf5 java.util.Map.Entry\cf4 ;\
import \cf5 javax.crypto.interfaces.DHPrivateKey\cf4 ;\
import \cf5 javax.crypto.interfaces.DHPublicKey\cf4 ;\
import \cf5 javax.security.auth.Subject\cf4 ;\
import \cf5 javax.security.auth.callback.Callback\cf4 ;\
import \cf5 javax.security.auth.callback.CallbackHandler\cf4 ;\
import \cf5 javax.security.auth.callback.PasswordCallback\cf4 ;\
import \cf5 javax.security.auth.login.FailedLoginException\cf4 ;\
import \cf5 javax.security.auth.login.LoginException\cf4 ;\
import \cf5 sun.security.ec.ECParameters\cf4 ;\
import \cf5 sun.security.pkcs11.Secmod.DbMode\cf4 ;\
import \cf5 sun.security.pkcs11.Secmod.Module\cf4 ;\
import \cf5 sun.security.pkcs11.Secmod.ModuleType\cf4 ;\
import \cf5 sun.security.pkcs11.wrapper.CK_C_INITIALIZE_ARGS\cf4 ;\
import \cf5 sun.security.pkcs11.wrapper.CK_INFO\cf4 ;\
import \cf5 sun.security.pkcs11.wrapper.CK_MECHANISM_INFO\cf4 ;\
import \cf5 sun.security.pkcs11.wrapper.CK_SLOT_INFO\cf4 ;\
import \cf5 sun.security.pkcs11.wrapper.Functions\cf4 ;\
import \cf5 sun.security.pkcs11.wrapper.PKCS11\cf4 ;\
import \cf5 sun.security.pkcs11.wrapper.PKCS11Exception\cf4 ;\
import \cf5 sun.security.util.Debug\cf4 ;\
import \cf5 sun.security.util.ResourcesMgr\cf4 ;\
\
public final class \cf5 SunPKCS11 \cf4 extends \cf5 AuthProvider \{\
    \cf4 private static final long \cf5 serialVersionUID = -\cf6 1354835039035306505L\cf4 ;\
    static final \cf5 Debug debug = Debug.getInstance(\cf7 "sunpkcs11"\cf5 )\cf4 ;\
    private static int \cf5 dummyConfigId\cf4 ;\
    final \cf5 PKCS11 p11\cf4 ;\
    private final \cf5 String configName\cf4 ;\
    final \cf5 Config config\cf4 ;\
    final long \cf5 slotID\cf4 ;\
    private \cf5 CallbackHandler pHandler\cf4 ;\
    private final \cf5 Object LOCK_HANDLER\cf4 ;\
    final boolean \cf5 removable\cf4 ;\
    final \cf5 Module nssModule\cf4 ;\
    final boolean \cf5 nssUseSecmodTrust\cf4 ;\
    private volatile \cf5 Token token\cf4 ;\
    private \cf5 SunPKCS11.TokenPoller poller\cf4 ;\
    private static final \cf5 Map<Integer\cf4 , \cf5 List<SunPKCS11.Descriptor>> descriptors = \cf4 new \cf5 HashMap()\cf4 ;\
    private static final \cf5 String MD = \cf7 "MessageDigest"\cf4 ;\
    private static final \cf5 String SIG = \cf7 "Signature"\cf4 ;\
    private static final \cf5 String KPG = \cf7 "KeyPairGenerator"\cf4 ;\
    private static final \cf5 String KG = \cf7 "KeyGenerator"\cf4 ;\
    private static final \cf5 String AGP = \cf7 "AlgorithmParameters"\cf4 ;\
    private static final \cf5 String KF = \cf7 "KeyFactory"\cf4 ;\
    private static final \cf5 String SKF = \cf7 "SecretKeyFactory"\cf4 ;\
    private static final \cf5 String CIP = \cf7 "Cipher"\cf4 ;\
    private static final \cf5 String MAC = \cf7 "Mac"\cf4 ;\
    private static final \cf5 String KA = \cf7 "KeyAgreement"\cf4 ;\
    private static final \cf5 String KS = \cf7 "KeyStore"\cf4 ;\
    private static final \cf5 String SR = \cf7 "SecureRandom"\cf4 ;\
\
    \cf5 Token getToken() \{\
        \cf4 return this\cf5 .token\cf4 ;\
    \cf5 \}\
\
    \cf4 public \cf5 SunPKCS11() \{\
        \cf4 super\cf5 (\cf7 "SunPKCS11-Dummy"\cf4 , \cf6 1.8D\cf4 , \cf7 "SunPKCS11-Dummy"\cf5 )\cf4 ;\
        this\cf5 .LOCK_HANDLER = \cf4 new \cf5 Object()\cf4 ;\
        throw new \cf5 ProviderException(\cf7 "SunPKCS11 requires configuration file argument"\cf5 )\cf4 ;\
    \cf5 \}\
\
    \cf4 public \cf5 SunPKCS11(String var1) \{\
        \cf4 this\cf5 ((String)checkNull(var1)\cf4 , \cf5 (InputStream)\cf4 null\cf5 )\cf4 ;\
    \cf5 \}\
\
    \cf4 public \cf5 SunPKCS11(InputStream var1) \{\
        \cf4 this\cf5 (getDummyConfigName()\cf4 , \cf5 (InputStream)checkNull(var1))\cf4 ;\
    \cf5 \}\
\
    \cf4 private static \cf5 <T> T checkNull(T var0) \{\
        \cf4 if \cf5 (var0 == \cf4 null\cf5 ) \{\
            \cf4 throw new \cf5 NullPointerException()\cf4 ;\
        \cf5 \} \cf4 else \cf5 \{\
            \cf4 return \cf5 var0\cf4 ;\
        \cf5 \}\
    \}\
\
    \cf4 private static synchronized \cf5 String getDummyConfigName() \{\
        \cf4 int \cf5 var0 = ++dummyConfigId\cf4 ;\
        return \cf7 "---DummyConfig-" \cf5 + var0 + \cf7 "---"\cf4 ;\
    \cf5 \}\
\
    
\f2\i \cf8 /** 
\f3\b @deprecated 
\f2\b0 */\
    
\f1\i0 \cf5 @Deprecated\
    \cf4 public \cf5 SunPKCS11(String var1\cf4 , \cf5 InputStream var2) \{\
        \cf4 super\cf5 (\cf7 "SunPKCS11-" \cf5 + Config.getConfig(var1\cf4 , \cf5 var2).getName()\cf4 , \cf6 1.8D\cf4 , \cf5 Config.getConfig(var1\cf4 , \cf5 var2).getDescription())\cf4 ;\
        this\cf5 .LOCK_HANDLER = \cf4 new \cf5 Object()\cf4 ;\
        this\cf5 .configName = var1\cf4 ;\
        this\cf5 .config = Config.removeConfig(var1)\cf4 ;\
        if \cf5 (debug != \cf4 null\cf5 ) \{\
            System.out.println(\cf7 "SunPKCS11 loading " \cf5 + var1)\cf4 ;\
        \cf5 \}\
\
        String var3 = \cf4 this\cf5 .config.getLibrary()\cf4 ;\
        \cf5 String var4 = \cf4 this\cf5 .config.getFunctionList()\cf4 ;\
        long \cf5 var5 = (\cf4 long\cf5 )\cf4 this\cf5 .config.getSlotID()\cf4 ;\
        int \cf5 var7 = \cf4 this\cf5 .config.getSlotListIndex()\cf4 ;\
        boolean \cf5 var8 = \cf4 this\cf5 .config.getNssUseSecmod()\cf4 ;\
        boolean \cf5 var9 = \cf4 this\cf5 .config.getNssUseSecmodTrust()\cf4 ;\
        \cf5 Module var10 = \cf4 null;\
        \cf5 String var13\cf4 ;\
        if \cf5 (var8) \{\
            Secmod var11 = Secmod.getInstance()\cf4 ;\
            \cf5 DbMode var12 = \cf4 this\cf5 .config.getNssDbMode()\cf4 ;\
\
            \cf5 String var14\cf4 ;\
            try \cf5 \{\
                var13 = \cf4 this\cf5 .config.getNssLibraryDirectory()\cf4 ;\
                \cf5 var14 = \cf4 this\cf5 .config.getNssSecmodDirectory()\cf4 ;\
                boolean \cf5 var15 = \cf4 this\cf5 .config.getNssOptimizeSpace()\cf4 ;\
                if \cf5 (var11.isInitialized()) \{\
                    String var16\cf4 ;\
                    if \cf5 (var14 != \cf4 null\cf5 ) \{\
                        var16 = var11.getConfigDir()\cf4 ;\
                        if \cf5 (var16 != \cf4 null \cf5 && !var16.equals(var14)) \{\
                            \cf4 throw new \cf5 ProviderException(\cf7 "Secmod directory " \cf5 + var14 + \cf7 " invalid, NSS already initialized with " \cf5 + var16)\cf4 ;\
                        \cf5 \}\
                    \}\
\
                    \cf4 if \cf5 (var13 != \cf4 null\cf5 ) \{\
                        var16 = var11.getLibDir()\cf4 ;\
                        if \cf5 (var16 != \cf4 null \cf5 && !var16.equals(var13)) \{\
                            \cf4 throw new \cf5 ProviderException(\cf7 "NSS library directory " \cf5 + var13 + \cf7 " invalid, NSS already initialized with " \cf5 + var16)\cf4 ;\
                        \cf5 \}\
                    \}\
                \} \cf4 else \cf5 \{\
                    \cf4 if \cf5 (var12 != DbMode.NO_DB) \{\
                        \cf4 if \cf5 (var14 == \cf4 null\cf5 ) \{\
                            \cf4 throw new \cf5 ProviderException(\cf7 "Secmod not initialized and nssSecmodDirectory not specified"\cf5 )\cf4 ;\
                        \cf5 \}\
                    \} \cf4 else if \cf5 (var14 != \cf4 null\cf5 ) \{\
                        \cf4 throw new \cf5 ProviderException(\cf7 "nssSecmodDirectory must not be specified in noDb mode"\cf5 )\cf4 ;\
                    \cf5 \}\
\
                    var11.initialize(var12\cf4 , \cf5 var14\cf4 , \cf5 var13\cf4 , \cf5 var15)\cf4 ;\
                \cf5 \}\
            \} \cf4 catch \cf5 (IOException var20) \{\
                \cf4 throw new \cf5 ProviderException(\cf7 "Could not initialize NSS"\cf4 , \cf5 var20)\cf4 ;\
            \cf5 \}\
\
            List var26 = var11.getModules()\cf4 ;\
            if \cf5 (\cf4 this\cf5 .config.getShowInfo()) \{\
                System.out.println(\cf7 "NSS modules: " \cf5 + var26)\cf4 ;\
            \cf5 \}\
\
            var14 = \cf4 this\cf5 .config.getNssModule()\cf4 ;\
            if \cf5 (var14 == \cf4 null\cf5 ) \{\
                var10 = var11.getModule(ModuleType.FIPS)\cf4 ;\
                if \cf5 (var10 != \cf4 null\cf5 ) \{\
                    var14 = \cf7 "fips"\cf4 ;\
                \cf5 \} \cf4 else \cf5 \{\
                    var14 = var12 == DbMode.NO_DB ? \cf7 "crypto" \cf5 : \cf7 "keystore"\cf4 ;\
                \cf5 \}\
            \}\
\
            \cf4 if \cf5 (var14.equals(\cf7 "fips"\cf5 )) \{\
                var10 = var11.getModule(ModuleType.FIPS)\cf4 ;\
                \cf5 var9 = \cf4 true;\
                \cf5 var4 = \cf7 "FC_GetFunctionList"\cf4 ;\
            \cf5 \} \cf4 else if \cf5 (var14.equals(\cf7 "keystore"\cf5 )) \{\
                var10 = var11.getModule(ModuleType.KEYSTORE)\cf4 ;\
                \cf5 var9 = \cf4 true;\
            \cf5 \} \cf4 else if \cf5 (var14.equals(\cf7 "crypto"\cf5 )) \{\
                var10 = var11.getModule(ModuleType.CRYPTO)\cf4 ;\
            \cf5 \} \cf4 else if \cf5 (var14.equals(\cf7 "trustanchors"\cf5 )) \{\
                var10 = var11.getModule(ModuleType.TRUSTANCHOR)\cf4 ;\
                \cf5 var9 = \cf4 true;\
            \cf5 \} \cf4 else \cf5 \{\
                \cf4 if \cf5 (!var14.startsWith(\cf7 "external-"\cf5 )) \{\
                    \cf4 throw new \cf5 ProviderException(\cf7 "Unknown NSS module: " \cf5 + var14)\cf4 ;\
                \cf5 \}\
\
                \cf4 int \cf5 var27\cf4 ;\
                try \cf5 \{\
                    var27 = Integer.parseInt(var14.substring(\cf7 "external-"\cf5 .length()))\cf4 ;\
                \cf5 \} \cf4 catch \cf5 (NumberFormatException var19) \{\
                    var27 = -\cf6 1\cf4 ;\
                \cf5 \}\
\
                \cf4 if \cf5 (var27 < \cf6 1\cf5 ) \{\
                    \cf4 throw new \cf5 ProviderException(\cf7 "Invalid external module: " \cf5 + var14)\cf4 ;\
                \cf5 \}\
\
                \cf4 int \cf5 var30 = \cf6 0\cf4 ;\
                \cf5 Iterator var17 = var26.iterator()\cf4 ;\
\
                while\cf5 (var17.hasNext()) \{\
                    Module var18 = (Module)var17.next()\cf4 ;\
                    if \cf5 (var18.getType() == ModuleType.EXTERNAL) \{\
                        ++var30\cf4 ;\
                        if \cf5 (var30 == var27) \{\
                            var10 = var18\cf4 ;\
                            break;\
                        \cf5 \}\
                    \}\
                \}\
\
                \cf4 if \cf5 (var10 == \cf4 null\cf5 ) \{\
                    \cf4 throw new \cf5 ProviderException(\cf7 "Invalid module " \cf5 + var14 + \cf7 ": only " \cf5 + var30 + \cf7 " external NSS modules available"\cf5 )\cf4 ;\
                \cf5 \}\
            \}\
\
            \cf4 if \cf5 (var10 == \cf4 null\cf5 ) \{\
                \cf4 throw new \cf5 ProviderException(\cf7 "NSS module not available: " \cf5 + var14)\cf4 ;\
            \cf5 \}\
\
            \cf4 if \cf5 (var10.hasInitializedProvider()) \{\
                \cf4 throw new \cf5 ProviderException(\cf7 "Secmod module already configured"\cf5 )\cf4 ;\
            \cf5 \}\
\
            var3 = var10.libraryName\cf4 ;\
            \cf5 var7 = var10.slot\cf4 ;\
        \cf5 \}\
\
        \cf4 this\cf5 .nssUseSecmodTrust = var9\cf4 ;\
        this\cf5 .nssModule = var10\cf4 ;\
        \cf5 File var23 = \cf4 new \cf5 File(var3)\cf4 ;\
        if \cf5 (!var23.getName().equals(var3) && !(\cf4 new \cf5 File(var3)).isFile()) \{\
            String var25 = \cf7 "Library " \cf5 + var3 + \cf7 " does not exist"\cf4 ;\
            if \cf5 (\cf4 this\cf5 .config.getHandleStartupErrors() == \cf6 1\cf5 ) \{\
                \cf4 throw new \cf5 ProviderException(var25)\cf4 ;\
            \cf5 \} \cf4 else \cf5 \{\
                \cf4 throw new \cf5 UnsupportedOperationException(var25)\cf4 ;\
            \cf5 \}\
        \} \cf4 else \cf5 \{\
            \cf4 try \cf5 \{\
                \cf4 if \cf5 (debug != \cf4 null\cf5 ) \{\
                    debug.println(\cf7 "Initializing PKCS#11 library " \cf5 + var3)\cf4 ;\
                \cf5 \}\
\
                CK_C_INITIALIZE_ARGS var24 = \cf4 new \cf5 CK_C_INITIALIZE_ARGS()\cf4 ;\
                \cf5 var13 = \cf4 this\cf5 .config.getNssArgs()\cf4 ;\
                if \cf5 (var13 != \cf4 null\cf5 ) \{\
                    var24.pReserved = var13\cf4 ;\
                \cf5 \}\
\
                var24.flags = \cf6 2L\cf4 ;\
\
                \cf5 PKCS11 var28\cf4 ;\
                try \cf5 \{\
                    var28 = PKCS11.getInstance(var3\cf4 , \cf5 var4\cf4 , \cf5 var24\cf4 , this\cf5 .config.getOmitInitialize())\cf4 ;\
                \cf5 \} \cf4 catch \cf5 (PKCS11Exception var21) \{\
                    \cf4 if \cf5 (debug != \cf4 null\cf5 ) \{\
                        debug.println(\cf7 "Multi-threaded initialization failed: " \cf5 + var21)\cf4 ;\
                    \cf5 \}\
\
                    \cf4 if \cf5 (!\cf4 this\cf5 .config.getAllowSingleThreadedModules()) \{\
                        \cf4 throw \cf5 var21\cf4 ;\
                    \cf5 \}\
\
                    \cf4 if \cf5 (var13 == \cf4 null\cf5 ) \{\
                        var24 = \cf4 null;\
                    \cf5 \} \cf4 else \cf5 \{\
                        var24.flags = \cf6 0L\cf4 ;\
                    \cf5 \}\
\
                    var28 = PKCS11.getInstance(var3\cf4 , \cf5 var4\cf4 , \cf5 var24\cf4 , this\cf5 .config.getOmitInitialize())\cf4 ;\
                \cf5 \}\
\
                \cf4 this\cf5 .p11 = var28\cf4 ;\
                \cf5 CK_INFO var29 = \cf4 this\cf5 .p11.C_GetInfo()\cf4 ;\
                if \cf5 (var29.cryptokiVersion.major < \cf6 2\cf5 ) \{\
                    \cf4 throw new \cf5 ProviderException(\cf7 "Only PKCS#11 v2.0 and later supported, library version is v" \cf5 + var29.cryptokiVersion)\cf4 ;\
                \cf5 \} \cf4 else \cf5 \{\
                    \cf4 boolean \cf5 var32 = \cf4 this\cf5 .config.getShowInfo()\cf4 ;\
                    if \cf5 (var32) \{\
                        System.out.println(\cf7 "Information for provider " \cf5 + \cf4 this\cf5 .getName())\cf4 ;\
                        \cf5 System.out.println(\cf7 "Library info:"\cf5 )\cf4 ;\
                        \cf5 System.out.println(var29)\cf4 ;\
                    \cf5 \}\
\
                    \cf4 if \cf5 (var5 < \cf6 0L \cf5 || var32) \{\
                        \cf4 long\cf5 [] var31 = \cf4 this\cf5 .p11.C_GetSlotList(\cf4 false\cf5 )\cf4 ;\
                        if \cf5 (var32) \{\
                            System.out.println(\cf7 "All slots: " \cf5 + toString(var31))\cf4 ;\
                            \cf5 var31 = \cf4 this\cf5 .p11.C_GetSlotList(\cf4 true\cf5 )\cf4 ;\
                            \cf5 System.out.println(\cf7 "Slots with tokens: " \cf5 + toString(var31))\cf4 ;\
                        \cf5 \}\
\
                        \cf4 if \cf5 (var5 < \cf6 0L\cf5 ) \{\
                            \cf4 if \cf5 (var7 < \cf6 0 \cf5 || var7 >= var31.length) \{\
                                \cf4 throw new \cf5 ProviderException(\cf7 "slotListIndex is " \cf5 + var7 + \cf7 " but token only has " \cf5 + var31.length + \cf7 " slots"\cf5 )\cf4 ;\
                            \cf5 \}\
\
                            var5 = var31[var7]\cf4 ;\
                        \cf5 \}\
                    \}\
\
                    \cf4 this\cf5 .slotID = var5\cf4 ;\
                    \cf5 CK_SLOT_INFO var33 = \cf4 this\cf5 .p11.C_GetSlotInfo(var5)\cf4 ;\
                    this\cf5 .removable = (var33.flags & \cf6 2L\cf5 ) != \cf6 0L\cf4 ;\
                    this\cf5 .initToken(var33)\cf4 ;\
                    if \cf5 (var10 != \cf4 null\cf5 ) \{\
                        var10.setProvider(\cf4 this\cf5 )\cf4 ;\
                    \cf5 \}\
\
                \}\
            \} \cf4 catch \cf5 (Exception var22) \{\
                \cf4 if \cf5 (\cf4 this\cf5 .config.getHandleStartupErrors() == \cf6 2\cf5 ) \{\
                    \cf4 throw new \cf5 UnsupportedOperationException(\cf7 "Initialization failed"\cf4 , \cf5 var22)\cf4 ;\
                \cf5 \} \cf4 else \cf5 \{\
                    \cf4 throw new \cf5 ProviderException(\cf7 "Initialization failed"\cf4 , \cf5 var22)\cf4 ;\
                \cf5 \}\
            \}\
        \}\
    \}\
\
    \cf4 private static \cf5 String toString(\cf4 long\cf5 [] var0) \{\
        \cf4 if \cf5 (var0.length == \cf6 0\cf5 ) \{\
            \cf4 return \cf7 "(none)"\cf4 ;\
        \cf5 \} \cf4 else \cf5 \{\
            StringBuilder var1 = \cf4 new \cf5 StringBuilder()\cf4 ;\
            \cf5 var1.append(var0[\cf6 0\cf5 ])\cf4 ;\
\
            for\cf5 (\cf4 int \cf5 var2 = \cf6 1\cf4 ; \cf5 var2 < var0.length\cf4 ; \cf5 ++var2) \{\
                var1.append(\cf7 ", "\cf5 )\cf4 ;\
                \cf5 var1.append(var0[var2])\cf4 ;\
            \cf5 \}\
\
            \cf4 return \cf5 var1.toString()\cf4 ;\
        \cf5 \}\
    \}\
\
    \cf4 public boolean \cf5 equals(Object var1) \{\
        \cf4 return this \cf5 == var1\cf4 ;\
    \cf5 \}\
\
    \cf4 public int \cf5 hashCode() \{\
        \cf4 return \cf5 System.identityHashCode(\cf4 this\cf5 )\cf4 ;\
    \cf5 \}\
\
    \cf4 private static \cf5 String[] s(String... var0) \{\
        \cf4 return \cf5 var0\cf4 ;\
    \cf5 \}\
\
    \cf4 private static int\cf5 [] m(\cf4 long \cf5 var0) \{\
        \cf4 return new int\cf5 []\{(\cf4 int\cf5 )var0\}\cf4 ;\
    \cf5 \}\
\
    \cf4 private static int\cf5 [] m(\cf4 long \cf5 var0\cf4 , long \cf5 var2) \{\
        \cf4 return new int\cf5 []\{(\cf4 int\cf5 )var0\cf4 , \cf5 (\cf4 int\cf5 )var2\}\cf4 ;\
    \cf5 \}\
\
    \cf4 private static int\cf5 [] m(\cf4 long \cf5 var0\cf4 , long \cf5 var2\cf4 , long \cf5 var4) \{\
        \cf4 return new int\cf5 []\{(\cf4 int\cf5 )var0\cf4 , \cf5 (\cf4 int\cf5 )var2\cf4 , \cf5 (\cf4 int\cf5 )var4\}\cf4 ;\
    \cf5 \}\
\
    \cf4 private static int\cf5 [] m(\cf4 long \cf5 var0\cf4 , long \cf5 var2\cf4 , long \cf5 var4\cf4 , long \cf5 var6) \{\
        \cf4 return new int\cf5 []\{(\cf4 int\cf5 )var0\cf4 , \cf5 (\cf4 int\cf5 )var2\cf4 , \cf5 (\cf4 int\cf5 )var4\cf4 , \cf5 (\cf4 int\cf5 )var6\}\cf4 ;\
    \cf5 \}\
\
    \cf4 private static void \cf5 d(String var0\cf4 , \cf5 String var1\cf4 , \cf5 String var2\cf4 , int\cf5 [] var3) \{\
        register(\cf4 new \cf5 SunPKCS11.Descriptor(var0\cf4 , \cf5 var1\cf4 , \cf5 var2\cf4 , \cf5 (String[])\cf4 null, \cf5 var3))\cf4 ;\
    \cf5 \}\
\
    \cf4 private static void \cf5 d(String var0\cf4 , \cf5 String var1\cf4 , \cf5 String var2\cf4 , \cf5 String[] var3\cf4 , int\cf5 [] var4) \{\
        register(\cf4 new \cf5 SunPKCS11.Descriptor(var0\cf4 , \cf5 var1\cf4 , \cf5 var2\cf4 , \cf5 var3\cf4 , \cf5 var4))\cf4 ;\
    \cf5 \}\
\
    \cf4 private static void \cf5 register(SunPKCS11.Descriptor var0) \{\
        \cf4 for\cf5 (\cf4 int \cf5 var1 = \cf6 0\cf4 ; \cf5 var1 < var0.mechanisms.length\cf4 ; \cf5 ++var1) \{\
            \cf4 int \cf5 var2 = var0.mechanisms[var1]\cf4 ;\
            \cf5 Integer var3 = var2\cf4 ;\
            \cf5 Object var4 = (List)descriptors.get(var3)\cf4 ;\
            if \cf5 (var4 == \cf4 null\cf5 ) \{\
                var4 = \cf4 new \cf5 ArrayList()\cf4 ;\
                \cf5 descriptors.put(var3\cf4 , \cf5 var4)\cf4 ;\
            \cf5 \}\
\
            ((List)var4).add(var0)\cf4 ;\
        \cf5 \}\
\
    \}\
\
    \cf4 private void \cf5 createPoller() \{\
        \cf4 if \cf5 (\cf4 this\cf5 .poller == \cf4 null\cf5 ) \{\
            SunPKCS11.TokenPoller var1 = \cf4 new \cf5 SunPKCS11.TokenPoller(\cf4 this\cf5 )\cf4 ;\
            \cf5 Thread var2 = \cf4 new \cf5 Thread(var1\cf4 , \cf7 "Poller " \cf5 + \cf4 this\cf5 .getName())\cf4 ;\
            \cf5 var2.setDaemon(\cf4 true\cf5 )\cf4 ;\
            \cf5 var2.setPriority(\cf6 1\cf5 )\cf4 ;\
            \cf5 var2.start()\cf4 ;\
            this\cf5 .poller = var1\cf4 ;\
        \cf5 \}\
    \}\
\
    \cf4 private void \cf5 destroyPoller() \{\
        \cf4 if \cf5 (\cf4 this\cf5 .poller != \cf4 null\cf5 ) \{\
            \cf4 this\cf5 .poller.disable()\cf4 ;\
            this\cf5 .poller = \cf4 null;\
        \cf5 \}\
\
    \}\
\
    \cf4 private boolean \cf5 hasValidToken() \{\
        Token var1 = \cf4 this\cf5 .token\cf4 ;\
        return \cf5 var1 != \cf4 null \cf5 && var1.isValid()\cf4 ;\
    \cf5 \}\
\
    \cf4 synchronized void \cf5 uninitToken(Token var1) \{\
        \cf4 if \cf5 (\cf4 this\cf5 .token == var1) \{\
            \cf4 this\cf5 .destroyPoller()\cf4 ;\
            this\cf5 .token = \cf4 null;\
            \cf5 AccessController.doPrivileged(\cf4 new \cf5 PrivilegedAction<Object>() \{\
                \cf4 public \cf5 Object run() \{\
                    SunPKCS11.\cf4 this\cf5 .clear()\cf4 ;\
                    return null;\
                \cf5 \}\
            \})\cf4 ;\
            this\cf5 .createPoller()\cf4 ;\
        \cf5 \}\
    \}\
\
    \cf4 private void \cf5 initToken(CK_SLOT_INFO var1) \cf4 throws \cf5 PKCS11Exception \{\
        \cf4 if \cf5 (var1 == \cf4 null\cf5 ) \{\
            var1 = \cf4 this\cf5 .p11.C_GetSlotInfo(\cf4 this\cf5 .slotID)\cf4 ;\
        \cf5 \}\
\
        \cf4 if \cf5 (\cf4 this\cf5 .removable && (var1.flags & \cf6 1L\cf5 ) == \cf6 0L\cf5 ) \{\
            \cf4 this\cf5 .createPoller()\cf4 ;\
        \cf5 \} \cf4 else \cf5 \{\
            \cf4 this\cf5 .destroyPoller()\cf4 ;\
            boolean \cf5 var2 = \cf4 this\cf5 .config.getShowInfo()\cf4 ;\
            if \cf5 (var2) \{\
                System.out.println(\cf7 "Slot info for slot " \cf5 + \cf4 this\cf5 .slotID + \cf7 ":"\cf5 )\cf4 ;\
                \cf5 System.out.println(var1)\cf4 ;\
            \cf5 \}\
\
            \cf4 final \cf5 Token var3 = \cf4 new \cf5 Token(\cf4 this\cf5 )\cf4 ;\
            if \cf5 (var2) \{\
                System.out.println(\cf7 "Token info for token in slot " \cf5 + \cf4 this\cf5 .slotID + \cf7 ":"\cf5 )\cf4 ;\
                \cf5 System.out.println(var3.tokenInfo)\cf4 ;\
            \cf5 \}\
\
            \cf4 long\cf5 [] var4 = \cf4 this\cf5 .p11.C_GetMechanismList(\cf4 this\cf5 .slotID)\cf4 ;\
            final \cf5 HashMap var5 = \cf4 new \cf5 HashMap()\cf4 ;\
\
            \cf5 label79:\
            \cf4 for\cf5 (\cf4 int \cf5 var6 = \cf6 0\cf4 ; \cf5 var6 < var4.length\cf4 ; \cf5 ++var6) \{\
                \cf4 long \cf5 var7 = var4[var6]\cf4 ;\
                boolean \cf5 var9 = \cf4 this\cf5 .config.isEnabled(var7)\cf4 ;\
                if \cf5 (var2) \{\
                    CK_MECHANISM_INFO var10 = \cf4 this\cf5 .p11.C_GetMechanismInfo(\cf4 this\cf5 .slotID\cf4 , \cf5 var7)\cf4 ;\
                    \cf5 System.out.println(\cf7 "Mechanism " \cf5 + Functions.getMechanismName(var7) + \cf7 ":"\cf5 )\cf4 ;\
                    if \cf5 (!var9) \{\
                        System.out.println(\cf7 "DISABLED in configuration"\cf5 )\cf4 ;\
                    \cf5 \}\
\
                    System.out.println(var10)\cf4 ;\
                \cf5 \}\
\
                \cf4 if \cf5 (var9 && var7 >>> \cf6 32 \cf5 == \cf6 0L\cf5 ) \{\
                    \cf4 int \cf5 var19 = (\cf4 int\cf5 )var7\cf4 ;\
                    \cf5 Integer var11 = var19\cf4 ;\
                    \cf5 List var12 = (List)descriptors.get(var11)\cf4 ;\
                    if \cf5 (var12 != \cf4 null\cf5 ) \{\
                        Iterator var13 = var12.iterator()\cf4 ;\
\
                        while\cf5 (\cf4 true\cf5 ) \{\
                            \cf4 while\cf5 (\cf4 true\cf5 ) \{\
                                \cf4 if \cf5 (!var13.hasNext()) \{\
                                    \cf4 continue \cf5 label79\cf4 ;\
                                \cf5 \}\
\
                                SunPKCS11.Descriptor var14 = (SunPKCS11.Descriptor)var13.next()\cf4 ;\
                                \cf5 Integer var15 = (Integer)var5.get(var14)\cf4 ;\
                                if \cf5 (var15 == \cf4 null\cf5 ) \{\
                                    var5.put(var14\cf4 , \cf5 var11)\cf4 ;\
                                \cf5 \} \cf4 else \cf5 \{\
                                    \cf4 int \cf5 var16 = var15\cf4 ;\
\
                                    for\cf5 (\cf4 int \cf5 var17 = \cf6 0\cf4 ; \cf5 var17 < var14.mechanisms.length\cf4 ; \cf5 ++var17) \{\
                                        \cf4 int \cf5 var18 = var14.mechanisms[var17]\cf4 ;\
                                        if \cf5 (var19 == var18) \{\
                                            var5.put(var14\cf4 , \cf5 var11)\cf4 ;\
                                            break;\
                                        \cf5 \}\
\
                                        \cf4 if \cf5 (var16 == var18) \{\
                                            \cf4 break;\
                                        \cf5 \}\
                                    \}\
                                \}\
                            \}\
                        \}\
                    \}\
                \}\
            \}\
\
            AccessController.doPrivileged(\cf4 new \cf5 PrivilegedAction<Object>() \{\
                \cf4 public \cf5 Object run() \{\
                    Iterator var1 = var5.entrySet().iterator()\cf4 ;\
\
                    while\cf5 (var1.hasNext()) \{\
                        Entry var2 = (Entry)var1.next()\cf4 ;\
                        \cf5 SunPKCS11.Descriptor var3x = (SunPKCS11.Descriptor)var2.getKey()\cf4 ;\
                        int \cf5 var4 = (Integer)var2.getValue()\cf4 ;\
                        \cf5 SunPKCS11.P11Service var5x = var3x.service(var3\cf4 , \cf5 var4)\cf4 ;\
                        \cf5 SunPKCS11.\cf4 this\cf5 .putService(var5x)\cf4 ;\
                    \cf5 \}\
\
                    \cf4 if \cf5 ((var3.tokenInfo.flags & \cf6 1L\cf5 ) != \cf6 0L \cf5 && SunPKCS11.\cf4 this\cf5 .config.isEnabled(\cf6 2147483424L\cf5 ) && !var3.sessionManager.lowMaxSessions()) \{\
                        SunPKCS11.\cf4 this\cf5 .putService(\cf4 new \cf5 SunPKCS11.P11Service(var3\cf4 , \cf7 "SecureRandom"\cf4 , \cf7 "PKCS11"\cf4 , \cf7 "sun.security.pkcs11.P11SecureRandom"\cf4 , \cf5 (String[])\cf4 null, \cf6 2147483424L\cf5 ))\cf4 ;\
                    \cf5 \}\
\
                    \cf4 if \cf5 (SunPKCS11.\cf4 this\cf5 .config.isEnabled(\cf6 2147483425L\cf5 )) \{\
                        SunPKCS11.\cf4 this\cf5 .putService(\cf4 new \cf5 SunPKCS11.P11Service(var3\cf4 , \cf7 "KeyStore"\cf4 , \cf7 "PKCS11"\cf4 , \cf7 "sun.security.pkcs11.P11KeyStore"\cf4 , \cf5 SunPKCS11.s(\cf7 "PKCS11-" \cf5 + SunPKCS11.\cf4 this\cf5 .config.getName())\cf4 , \cf6 2147483425L\cf5 ))\cf4 ;\
                    \cf5 \}\
\
                    \cf4 return null;\
                \cf5 \}\
            \})\cf4 ;\
            this\cf5 .token = var3\cf4 ;\
        \cf5 \}\
    \}\
\
    \cf4 public void \cf5 login(Subject var1\cf4 , \cf5 CallbackHandler var2) \cf4 throws \cf5 LoginException \{\
        SecurityManager var3 = System.getSecurityManager()\cf4 ;\
        if \cf5 (var3 != \cf4 null\cf5 ) \{\
            \cf4 if \cf5 (debug != \cf4 null\cf5 ) \{\
                debug.println(\cf7 "checking login permission"\cf5 )\cf4 ;\
            \cf5 \}\
\
            var3.checkPermission(\cf4 new \cf5 SecurityPermission(\cf7 "authProvider." \cf5 + \cf4 this\cf5 .getName()))\cf4 ;\
        \cf5 \}\
\
        \cf4 if \cf5 (!\cf4 this\cf5 .hasValidToken()) \{\
            \cf4 throw new \cf5 LoginException(\cf7 "No token present"\cf5 )\cf4 ;\
        \cf5 \} \cf4 else if \cf5 ((\cf4 this\cf5 .token.tokenInfo.flags & \cf6 4L\cf5 ) == \cf6 0L\cf5 ) \{\
            \cf4 if \cf5 (debug != \cf4 null\cf5 ) \{\
                debug.println(\cf7 "login operation not required for token - ignoring login request"\cf5 )\cf4 ;\
            \cf5 \}\
\
        \} \cf4 else \cf5 \{\
            \cf4 try \cf5 \{\
                \cf4 if \cf5 (\cf4 this\cf5 .token.isLoggedInNow((Session)\cf4 null\cf5 )) \{\
                    \cf4 if \cf5 (debug != \cf4 null\cf5 ) \{\
                        debug.println(\cf7 "user already logged in"\cf5 )\cf4 ;\
                    \cf5 \}\
\
                    \cf4 return;\
                \cf5 \}\
            \} \cf4 catch \cf5 (PKCS11Exception var18) \{\
                \cf4 ;\
            \cf5 \}\
\
            \cf4 char\cf5 [] var4 = \cf4 null;\
            if \cf5 ((\cf4 this\cf5 .token.tokenInfo.flags & \cf6 256L\cf5 ) == \cf6 0L\cf5 ) \{\
                CallbackHandler var5 = \cf4 this\cf5 .getCallbackHandler(var2)\cf4 ;\
                if \cf5 (var5 == \cf4 null\cf5 ) \{\
                    \cf4 throw new \cf5 LoginException(\cf7 "no password provided, and no callback handler available for retrieving password"\cf5 )\cf4 ;\
                \cf5 \}\
\
                MessageFormat var6 = \cf4 new \cf5 MessageFormat(ResourcesMgr.getString(\cf7 "PKCS11.Token.providerName.Password."\cf5 ))\cf4 ;\
                \cf5 Object[] var7 = \cf4 new \cf5 Object[]\{\cf4 this\cf5 .getName()\}\cf4 ;\
                \cf5 PasswordCallback var8 = \cf4 new \cf5 PasswordCallback(var6.format(var7)\cf4 , false\cf5 )\cf4 ;\
                \cf5 Callback[] var9 = \cf4 new \cf5 Callback[]\{var8\}\cf4 ;\
\
                try \cf5 \{\
                    var5.handle(var9)\cf4 ;\
                \cf5 \} \cf4 catch \cf5 (Exception var17) \{\
                    LoginException var11 = \cf4 new \cf5 LoginException(\cf7 "Unable to perform password callback"\cf5 )\cf4 ;\
                    \cf5 var11.initCause(var17)\cf4 ;\
                    throw \cf5 var11\cf4 ;\
                \cf5 \}\
\
                var4 = var8.getPassword()\cf4 ;\
                \cf5 var8.clearPassword()\cf4 ;\
                if \cf5 (var4 == \cf4 null \cf5 && debug != \cf4 null\cf5 ) \{\
                    debug.println(\cf7 "caller passed NULL pin"\cf5 )\cf4 ;\
                \cf5 \}\
            \}\
\
            Session var21 = \cf4 null;\
\
            try \cf5 \{\
                \cf4 try \cf5 \{\
                    var21 = \cf4 this\cf5 .token.getOpSession()\cf4 ;\
                    this\cf5 .p11.C_Login(var21.id()\cf4 , \cf6 1L\cf4 , \cf5 var4)\cf4 ;\
                    if \cf5 (debug != \cf4 null\cf5 ) \{\
                        debug.println(\cf7 "login succeeded"\cf5 )\cf4 ;\
                    \cf5 \}\
\
                    \cf4 return;\
                \cf5 \} \cf4 catch \cf5 (PKCS11Exception var19) \{\
                    \cf4 if \cf5 (var19.getErrorCode() != \cf6 256L\cf5 ) \{\
                        \cf4 if \cf5 (var19.getErrorCode() == \cf6 160L\cf5 ) \{\
                            FailedLoginException var23 = \cf4 new \cf5 FailedLoginException()\cf4 ;\
                            \cf5 var23.initCause(var19)\cf4 ;\
                            throw \cf5 var23\cf4 ;\
                        \cf5 \}\
\
                        LoginException var22 = \cf4 new \cf5 LoginException()\cf4 ;\
                        \cf5 var22.initCause(var19)\cf4 ;\
                        throw \cf5 var22\cf4 ;\
                    \cf5 \}\
                \}\
\
                \cf4 if \cf5 (debug != \cf4 null\cf5 ) \{\
                    debug.println(\cf7 "user already logged in"\cf5 )\cf4 ;\
                \cf5 \}\
            \} \cf4 finally \cf5 \{\
                \cf4 this\cf5 .token.releaseSession(var21)\cf4 ;\
                if \cf5 (var4 != \cf4 null\cf5 ) \{\
                    Arrays.fill(var4\cf4 , \cf7 ' '\cf5 )\cf4 ;\
                \cf5 \}\
\
            \}\
\
        \}\
    \}\
\
    \cf4 public void \cf5 logout() \cf4 throws \cf5 LoginException \{\
        SecurityManager var1 = System.getSecurityManager()\cf4 ;\
        if \cf5 (var1 != \cf4 null\cf5 ) \{\
            var1.checkPermission(\cf4 new \cf5 SecurityPermission(\cf7 "authProvider." \cf5 + \cf4 this\cf5 .getName()))\cf4 ;\
        \cf5 \}\
\
        \cf4 if \cf5 (\cf4 this\cf5 .hasValidToken()) \{\
            \cf4 if \cf5 ((\cf4 this\cf5 .token.tokenInfo.flags & \cf6 4L\cf5 ) == \cf6 0L\cf5 ) \{\
                \cf4 if \cf5 (debug != \cf4 null\cf5 ) \{\
                    debug.println(\cf7 "logout operation not required for token - ignoring logout request"\cf5 )\cf4 ;\
                \cf5 \}\
\
            \} \cf4 else \cf5 \{\
                \cf4 try \cf5 \{\
                    \cf4 if \cf5 (!\cf4 this\cf5 .token.isLoggedInNow((Session)\cf4 null\cf5 )) \{\
                        \cf4 if \cf5 (debug != \cf4 null\cf5 ) \{\
                            debug.println(\cf7 "user not logged in"\cf5 )\cf4 ;\
                        \cf5 \}\
\
                        \cf4 return;\
                    \cf5 \}\
                \} \cf4 catch \cf5 (PKCS11Exception var9) \{\
                    \cf4 ;\
                \cf5 \}\
\
                Session var2 = \cf4 null;\
\
                try \cf5 \{\
                    var2 = \cf4 this\cf5 .token.getOpSession()\cf4 ;\
                    this\cf5 .p11.C_Logout(var2.id())\cf4 ;\
                    if \cf5 (debug != \cf4 null\cf5 ) \{\
                        debug.println(\cf7 "logout succeeded"\cf5 )\cf4 ;\
                    \cf5 \}\
\
                    \cf4 return;\
                \cf5 \} \cf4 catch \cf5 (PKCS11Exception var10) \{\
                    \cf4 if \cf5 (var10.getErrorCode() != \cf6 257L\cf5 ) \{\
                        LoginException var4 = \cf4 new \cf5 LoginException()\cf4 ;\
                        \cf5 var4.initCause(var10)\cf4 ;\
                        throw \cf5 var4\cf4 ;\
                    \cf5 \}\
\
                    \cf4 if \cf5 (debug != \cf4 null\cf5 ) \{\
                        debug.println(\cf7 "user not logged in"\cf5 )\cf4 ;\
                    \cf5 \}\
                \} \cf4 finally \cf5 \{\
                    \cf4 this\cf5 .token.releaseSession(var2)\cf4 ;\
                \cf5 \}\
\
            \}\
        \}\
    \}\
\
    \cf4 public void \cf5 setCallbackHandler(CallbackHandler var1) \{\
        SecurityManager var2 = System.getSecurityManager()\cf4 ;\
        if \cf5 (var2 != \cf4 null\cf5 ) \{\
            var2.checkPermission(\cf4 new \cf5 SecurityPermission(\cf7 "authProvider." \cf5 + \cf4 this\cf5 .getName()))\cf4 ;\
        \cf5 \}\
\
        Object var3 = \cf4 this\cf5 .LOCK_HANDLER\cf4 ;\
        synchronized\cf5 (\cf4 this\cf5 .LOCK_HANDLER) \{\
            \cf4 this\cf5 .pHandler = var1\cf4 ;\
        \cf5 \}\
    \}\
\
    \cf4 private \cf5 CallbackHandler getCallbackHandler(CallbackHandler var1) \{\
        \cf4 if \cf5 (var1 != \cf4 null\cf5 ) \{\
            \cf4 return \cf5 var1\cf4 ;\
        \cf5 \} \cf4 else \cf5 \{\
            \cf4 if \cf5 (debug != \cf4 null\cf5 ) \{\
                debug.println(\cf7 "getting provider callback handler"\cf5 )\cf4 ;\
            \cf5 \}\
\
            Object var2 = \cf4 this\cf5 .LOCK_HANDLER\cf4 ;\
            synchronized\cf5 (\cf4 this\cf5 .LOCK_HANDLER) \{\
                \cf4 if \cf5 (\cf4 this\cf5 .pHandler != \cf4 null\cf5 ) \{\
                    \cf4 return this\cf5 .pHandler\cf4 ;\
                \cf5 \} \cf4 else \cf5 \{\
                    CallbackHandler var10000\cf4 ;\
                    try \cf5 \{\
                        \cf4 if \cf5 (debug != \cf4 null\cf5 ) \{\
                            debug.println(\cf7 "getting default callback handler"\cf5 )\cf4 ;\
                        \cf5 \}\
\
                        CallbackHandler var3 = (CallbackHandler)AccessController.doPrivileged(\cf4 new \cf5 PrivilegedExceptionAction<CallbackHandler>() \{\
                            \cf4 public \cf5 CallbackHandler run() \cf4 throws \cf5 Exception \{\
                                String var1 = Security.getProperty(\cf7 "auth.login.defaultCallbackHandler"\cf5 )\cf4 ;\
                                if \cf5 (var1 != \cf4 null \cf5 && var1.length() != \cf6 0\cf5 ) \{\
                                    Class var2 = Class.forName(var1\cf4 , true, \cf5 Thread.currentThread().getContextClassLoader())\cf4 ;\
                                    return \cf5 (CallbackHandler)var2.newInstance()\cf4 ;\
                                \cf5 \} \cf4 else \cf5 \{\
                                    \cf4 if \cf5 (SunPKCS11.debug != \cf4 null\cf5 ) \{\
                                        SunPKCS11.debug.println(\cf7 "no default handler set"\cf5 )\cf4 ;\
                                    \cf5 \}\
\
                                    \cf4 return null;\
                                \cf5 \}\
                            \}\
                        \})\cf4 ;\
                        this\cf5 .pHandler = var3\cf4 ;\
                        \cf5 var10000 = var3\cf4 ;\
                    \cf5 \} \cf4 catch \cf5 (PrivilegedActionException var5) \{\
                        \cf4 if \cf5 (debug != \cf4 null\cf5 ) \{\
                            debug.println(\cf7 "Unable to load default callback handler"\cf5 )\cf4 ;\
                            \cf5 var5.printStackTrace()\cf4 ;\
                        \cf5 \}\
\
                        \cf4 return null;\
                    \cf5 \}\
\
                    \cf4 return \cf5 var10000\cf4 ;\
                \cf5 \}\
            \}\
        \}\
    \}\
\
    \cf4 private \cf5 Object writeReplace() \cf4 throws \cf5 ObjectStreamException \{\
        \cf4 return new \cf5 SunPKCS11.SunPKCS11Rep(\cf4 this\cf5 )\cf4 ;\
    \cf5 \}\
\
    \cf4 static \cf5 \{\
        String var0 = \cf7 "sun.security.pkcs11.P11Digest"\cf4 ;\
        \cf5 String var1 = \cf7 "sun.security.pkcs11.P11MAC"\cf4 ;\
        \cf5 String var2 = \cf7 "sun.security.pkcs11.P11KeyPairGenerator"\cf4 ;\
        \cf5 String var3 = \cf7 "sun.security.pkcs11.P11KeyGenerator"\cf4 ;\
        \cf5 String var4 = \cf7 "sun.security.pkcs11.P11RSAKeyFactory"\cf4 ;\
        \cf5 String var5 = \cf7 "sun.security.pkcs11.P11DSAKeyFactory"\cf4 ;\
        \cf5 String var6 = \cf7 "sun.security.pkcs11.P11DHKeyFactory"\cf4 ;\
        \cf5 String var7 = \cf7 "sun.security.pkcs11.P11KeyAgreement"\cf4 ;\
        \cf5 String var8 = \cf7 "sun.security.pkcs11.P11SecretKeyFactory"\cf4 ;\
        \cf5 String var9 = \cf7 "sun.security.pkcs11.P11Cipher"\cf4 ;\
        \cf5 String var10 = \cf7 "sun.security.pkcs11.P11RSACipher"\cf4 ;\
        \cf5 String var11 = \cf7 "sun.security.pkcs11.P11Signature"\cf4 ;\
        \cf5 d(\cf7 "MessageDigest"\cf4 , \cf7 "MD2"\cf4 , \cf5 var0\cf4 , \cf5 m(\cf6 512L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "MessageDigest"\cf4 , \cf7 "MD5"\cf4 , \cf5 var0\cf4 , \cf5 m(\cf6 528L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "MessageDigest"\cf4 , \cf7 "SHA1"\cf4 , \cf5 var0\cf4 , \cf5 s(\cf7 "SHA"\cf4 , \cf7 "SHA-1"\cf4 , \cf7 "1.3.14.3.2.26"\cf4 , \cf7 "OID.1.3.14.3.2.26"\cf5 )\cf4 , \cf5 m(\cf6 544L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "MessageDigest"\cf4 , \cf7 "SHA-224"\cf4 , \cf5 var0\cf4 , \cf5 s(\cf7 "2.16.840.1.101.3.4.2.4"\cf4 , \cf7 "OID.2.16.840.1.101.3.4.2.4"\cf5 )\cf4 , \cf5 m(\cf6 597L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "MessageDigest"\cf4 , \cf7 "SHA-256"\cf4 , \cf5 var0\cf4 , \cf5 s(\cf7 "2.16.840.1.101.3.4.2.1"\cf4 , \cf7 "OID.2.16.840.1.101.3.4.2.1"\cf5 )\cf4 , \cf5 m(\cf6 592L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "MessageDigest"\cf4 , \cf7 "SHA-384"\cf4 , \cf5 var0\cf4 , \cf5 s(\cf7 "2.16.840.1.101.3.4.2.2"\cf4 , \cf7 "OID.2.16.840.1.101.3.4.2.2"\cf5 )\cf4 , \cf5 m(\cf6 608L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "MessageDigest"\cf4 , \cf7 "SHA-512"\cf4 , \cf5 var0\cf4 , \cf5 s(\cf7 "2.16.840.1.101.3.4.2.3"\cf4 , \cf7 "OID.2.16.840.1.101.3.4.2.3"\cf5 )\cf4 , \cf5 m(\cf6 624L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "Mac"\cf4 , \cf7 "HmacMD5"\cf4 , \cf5 var1\cf4 , \cf5 m(\cf6 529L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "Mac"\cf4 , \cf7 "HmacSHA1"\cf4 , \cf5 var1\cf4 , \cf5 s(\cf7 "1.2.840.113549.2.7"\cf4 , \cf7 "OID.1.2.840.113549.2.7"\cf5 )\cf4 , \cf5 m(\cf6 545L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "Mac"\cf4 , \cf7 "HmacSHA224"\cf4 , \cf5 var1\cf4 , \cf5 s(\cf7 "1.2.840.113549.2.8"\cf4 , \cf7 "OID.1.2.840.113549.2.8"\cf5 )\cf4 , \cf5 m(\cf6 598L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "Mac"\cf4 , \cf7 "HmacSHA256"\cf4 , \cf5 var1\cf4 , \cf5 s(\cf7 "1.2.840.113549.2.9"\cf4 , \cf7 "OID.1.2.840.113549.2.9"\cf5 )\cf4 , \cf5 m(\cf6 593L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "Mac"\cf4 , \cf7 "HmacSHA384"\cf4 , \cf5 var1\cf4 , \cf5 s(\cf7 "1.2.840.113549.2.10"\cf4 , \cf7 "OID.1.2.840.113549.2.10"\cf5 )\cf4 , \cf5 m(\cf6 609L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "Mac"\cf4 , \cf7 "HmacSHA512"\cf4 , \cf5 var1\cf4 , \cf5 s(\cf7 "1.2.840.113549.2.11"\cf4 , \cf7 "OID.1.2.840.113549.2.11"\cf5 )\cf4 , \cf5 m(\cf6 625L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "Mac"\cf4 , \cf7 "SslMacMD5"\cf4 , \cf5 var1\cf4 , \cf5 m(\cf6 896L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "Mac"\cf4 , \cf7 "SslMacSHA1"\cf4 , \cf5 var1\cf4 , \cf5 m(\cf6 897L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "KeyPairGenerator"\cf4 , \cf7 "RSA"\cf4 , \cf5 var2\cf4 , \cf5 m(\cf6 0L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "KeyPairGenerator"\cf4 , \cf7 "DSA"\cf4 , \cf5 var2\cf4 , \cf5 s(\cf7 "1.3.14.3.2.12"\cf4 , \cf7 "1.2.840.10040.4.1"\cf4 , \cf7 "OID.1.2.840.10040.4.1"\cf5 )\cf4 , \cf5 m(\cf6 16L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "KeyPairGenerator"\cf4 , \cf7 "DH"\cf4 , \cf5 var2\cf4 , \cf5 s(\cf7 "DiffieHellman"\cf5 )\cf4 , \cf5 m(\cf6 32L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "KeyPairGenerator"\cf4 , \cf7 "EC"\cf4 , \cf5 var2\cf4 , \cf5 m(\cf6 4160L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "KeyGenerator"\cf4 , \cf7 "ARCFOUR"\cf4 , \cf5 var3\cf4 , \cf5 s(\cf7 "RC4"\cf5 )\cf4 , \cf5 m(\cf6 272L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "KeyGenerator"\cf4 , \cf7 "DES"\cf4 , \cf5 var3\cf4 , \cf5 m(\cf6 288L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "KeyGenerator"\cf4 , \cf7 "DESede"\cf4 , \cf5 var3\cf4 , \cf5 m(\cf6 305L\cf4 , \cf6 304L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "KeyGenerator"\cf4 , \cf7 "AES"\cf4 , \cf5 var3\cf4 , \cf5 m(\cf6 4224L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "KeyGenerator"\cf4 , \cf7 "Blowfish"\cf4 , \cf5 var3\cf4 , \cf5 m(\cf6 4240L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "KeyFactory"\cf4 , \cf7 "RSA"\cf4 , \cf5 var4\cf4 , \cf5 m(\cf6 0L\cf4 , \cf6 1L\cf4 , \cf6 3L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "KeyFactory"\cf4 , \cf7 "DSA"\cf4 , \cf5 var5\cf4 , \cf5 s(\cf7 "1.3.14.3.2.12"\cf4 , \cf7 "1.2.840.10040.4.1"\cf4 , \cf7 "OID.1.2.840.10040.4.1"\cf5 )\cf4 , \cf5 m(\cf6 16L\cf4 , \cf6 17L\cf4 , \cf6 18L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "KeyFactory"\cf4 , \cf7 "DH"\cf4 , \cf5 var6\cf4 , \cf5 s(\cf7 "DiffieHellman"\cf5 )\cf4 , \cf5 m(\cf6 32L\cf4 , \cf6 33L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "KeyFactory"\cf4 , \cf7 "EC"\cf4 , \cf5 var6\cf4 , \cf5 m(\cf6 4160L\cf4 , \cf6 4176L\cf4 , \cf6 4161L\cf4 , \cf6 4162L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "AlgorithmParameters"\cf4 , \cf7 "EC"\cf4 , \cf7 "sun.security.ec.ECParameters"\cf4 , \cf5 s(\cf7 "1.2.840.10045.2.1"\cf5 )\cf4 , \cf5 m(\cf6 4160L\cf4 , \cf6 4176L\cf4 , \cf6 4161L\cf4 , \cf6 4162L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "KeyAgreement"\cf4 , \cf7 "DH"\cf4 , \cf5 var7\cf4 , \cf5 s(\cf7 "DiffieHellman"\cf5 )\cf4 , \cf5 m(\cf6 33L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "KeyAgreement"\cf4 , \cf7 "ECDH"\cf4 , \cf7 "sun.security.pkcs11.P11ECDHKeyAgreement"\cf4 , \cf5 m(\cf6 4176L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "SecretKeyFactory"\cf4 , \cf7 "ARCFOUR"\cf4 , \cf5 var8\cf4 , \cf5 s(\cf7 "RC4"\cf5 )\cf4 , \cf5 m(\cf6 273L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "SecretKeyFactory"\cf4 , \cf7 "DES"\cf4 , \cf5 var8\cf4 , \cf5 m(\cf6 290L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "SecretKeyFactory"\cf4 , \cf7 "DESede"\cf4 , \cf5 var8\cf4 , \cf5 m(\cf6 307L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "SecretKeyFactory"\cf4 , \cf7 "AES"\cf4 , \cf5 var8\cf4 , \cf5 s(\cf7 "2.16.840.1.101.3.4.1"\cf4 , \cf7 "OID.2.16.840.1.101.3.4.1"\cf5 )\cf4 , \cf5 m(\cf6 4226L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "SecretKeyFactory"\cf4 , \cf7 "Blowfish"\cf4 , \cf5 var8\cf4 , \cf5 m(\cf6 4241L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "Cipher"\cf4 , \cf7 "ARCFOUR"\cf4 , \cf5 var9\cf4 , \cf5 s(\cf7 "RC4"\cf5 )\cf4 , \cf5 m(\cf6 273L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "Cipher"\cf4 , \cf7 "DES/CBC/NoPadding"\cf4 , \cf5 var9\cf4 , \cf5 m(\cf6 290L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "Cipher"\cf4 , \cf7 "DES/CBC/PKCS5Padding"\cf4 , \cf5 var9\cf4 , \cf5 m(\cf6 293L\cf4 , \cf6 290L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "Cipher"\cf4 , \cf7 "DES/ECB/NoPadding"\cf4 , \cf5 var9\cf4 , \cf5 m(\cf6 289L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "Cipher"\cf4 , \cf7 "DES/ECB/PKCS5Padding"\cf4 , \cf5 var9\cf4 , \cf5 s(\cf7 "DES"\cf5 )\cf4 , \cf5 m(\cf6 289L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "Cipher"\cf4 , \cf7 "DESede/CBC/NoPadding"\cf4 , \cf5 var9\cf4 , \cf5 m(\cf6 307L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "Cipher"\cf4 , \cf7 "DESede/CBC/PKCS5Padding"\cf4 , \cf5 var9\cf4 , \cf5 m(\cf6 310L\cf4 , \cf6 307L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "Cipher"\cf4 , \cf7 "DESede/ECB/NoPadding"\cf4 , \cf5 var9\cf4 , \cf5 m(\cf6 306L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "Cipher"\cf4 , \cf7 "DESede/ECB/PKCS5Padding"\cf4 , \cf5 var9\cf4 , \cf5 s(\cf7 "DESede"\cf5 )\cf4 , \cf5 m(\cf6 306L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "Cipher"\cf4 , \cf7 "AES/CBC/NoPadding"\cf4 , \cf5 var9\cf4 , \cf5 m(\cf6 4226L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "Cipher"\cf4 , \cf7 "AES_128/CBC/NoPadding"\cf4 , \cf5 var9\cf4 , \cf5 s(\cf7 "2.16.840.1.101.3.4.1.2"\cf4 , \cf7 "OID.2.16.840.1.101.3.4.1.2"\cf5 )\cf4 , \cf5 m(\cf6 4226L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "Cipher"\cf4 , \cf7 "AES_192/CBC/NoPadding"\cf4 , \cf5 var9\cf4 , \cf5 s(\cf7 "2.16.840.1.101.3.4.1.22"\cf4 , \cf7 "OID.2.16.840.1.101.3.4.1.22"\cf5 )\cf4 , \cf5 m(\cf6 4226L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "Cipher"\cf4 , \cf7 "AES_256/CBC/NoPadding"\cf4 , \cf5 var9\cf4 , \cf5 s(\cf7 "2.16.840.1.101.3.4.1.42"\cf4 , \cf7 "OID.2.16.840.1.101.3.4.1.42"\cf5 )\cf4 , \cf5 m(\cf6 4226L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "Cipher"\cf4 , \cf7 "AES/CBC/PKCS5Padding"\cf4 , \cf5 var9\cf4 , \cf5 m(\cf6 4229L\cf4 , \cf6 4226L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "Cipher"\cf4 , \cf7 "AES/ECB/NoPadding"\cf4 , \cf5 var9\cf4 , \cf5 m(\cf6 4225L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "Cipher"\cf4 , \cf7 "AES_128/ECB/NoPadding"\cf4 , \cf5 var9\cf4 , \cf5 s(\cf7 "2.16.840.1.101.3.4.1.1"\cf4 , \cf7 "OID.2.16.840.1.101.3.4.1.1"\cf5 )\cf4 , \cf5 m(\cf6 4225L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "Cipher"\cf4 , \cf7 "AES_192/ECB/NoPadding"\cf4 , \cf5 var9\cf4 , \cf5 s(\cf7 "2.16.840.1.101.3.4.1.21"\cf4 , \cf7 "OID.2.16.840.1.101.3.4.1.21"\cf5 )\cf4 , \cf5 m(\cf6 4225L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "Cipher"\cf4 , \cf7 "AES_256/ECB/NoPadding"\cf4 , \cf5 var9\cf4 , \cf5 s(\cf7 "2.16.840.1.101.3.4.1.41"\cf4 , \cf7 "OID.2.16.840.1.101.3.4.1.41"\cf5 )\cf4 , \cf5 m(\cf6 4225L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "Cipher"\cf4 , \cf7 "AES/ECB/PKCS5Padding"\cf4 , \cf5 var9\cf4 , \cf5 s(\cf7 "AES"\cf5 )\cf4 , \cf5 m(\cf6 4225L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "Cipher"\cf4 , \cf7 "AES/CTR/NoPadding"\cf4 , \cf5 var9\cf4 , \cf5 m(\cf6 4230L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "Cipher"\cf4 , \cf7 "Blowfish/CBC/NoPadding"\cf4 , \cf5 var9\cf4 , \cf5 m(\cf6 4241L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "Cipher"\cf4 , \cf7 "Blowfish/CBC/PKCS5Padding"\cf4 , \cf5 var9\cf4 , \cf5 m(\cf6 4241L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "Cipher"\cf4 , \cf7 "RSA/ECB/PKCS1Padding"\cf4 , \cf5 var10\cf4 , \cf5 s(\cf7 "RSA"\cf5 )\cf4 , \cf5 m(\cf6 1L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "Cipher"\cf4 , \cf7 "RSA/ECB/NoPadding"\cf4 , \cf5 var10\cf4 , \cf5 m(\cf6 3L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "Signature"\cf4 , \cf7 "RawDSA"\cf4 , \cf5 var11\cf4 , \cf5 s(\cf7 "NONEwithDSA"\cf5 )\cf4 , \cf5 m(\cf6 17L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "Signature"\cf4 , \cf7 "DSA"\cf4 , \cf5 var11\cf4 , \cf5 s(\cf7 "SHA1withDSA"\cf4 , \cf7 "1.3.14.3.2.13"\cf4 , \cf7 "1.3.14.3.2.27"\cf4 , \cf7 "1.2.840.10040.4.3"\cf4 , \cf7 "OID.1.2.840.10040.4.3"\cf5 )\cf4 , \cf5 m(\cf6 18L\cf4 , \cf6 17L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "Signature"\cf4 , \cf7 "NONEwithECDSA"\cf4 , \cf5 var11\cf4 , \cf5 m(\cf6 4161L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "Signature"\cf4 , \cf7 "SHA1withECDSA"\cf4 , \cf5 var11\cf4 , \cf5 s(\cf7 "ECDSA"\cf4 , \cf7 "1.2.840.10045.4.1"\cf4 , \cf7 "OID.1.2.840.10045.4.1"\cf5 )\cf4 , \cf5 m(\cf6 4162L\cf4 , \cf6 4161L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "Signature"\cf4 , \cf7 "SHA224withECDSA"\cf4 , \cf5 var11\cf4 , \cf5 s(\cf7 "1.2.840.10045.4.3.1"\cf4 , \cf7 "OID.1.2.840.10045.4.3.1"\cf5 )\cf4 , \cf5 m(\cf6 4161L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "Signature"\cf4 , \cf7 "SHA256withECDSA"\cf4 , \cf5 var11\cf4 , \cf5 s(\cf7 "1.2.840.10045.4.3.2"\cf4 , \cf7 "OID.1.2.840.10045.4.3.2"\cf5 )\cf4 , \cf5 m(\cf6 4161L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "Signature"\cf4 , \cf7 "SHA384withECDSA"\cf4 , \cf5 var11\cf4 , \cf5 s(\cf7 "1.2.840.10045.4.3.3"\cf4 , \cf7 "OID.1.2.840.10045.4.3.3"\cf5 )\cf4 , \cf5 m(\cf6 4161L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "Signature"\cf4 , \cf7 "SHA512withECDSA"\cf4 , \cf5 var11\cf4 , \cf5 s(\cf7 "1.2.840.10045.4.3.4"\cf4 , \cf7 "OID.1.2.840.10045.4.3.4"\cf5 )\cf4 , \cf5 m(\cf6 4161L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "Signature"\cf4 , \cf7 "MD2withRSA"\cf4 , \cf5 var11\cf4 , \cf5 s(\cf7 "1.2.840.113549.1.1.2"\cf4 , \cf7 "OID.1.2.840.113549.1.1.2"\cf5 )\cf4 , \cf5 m(\cf6 4L\cf4 , \cf6 1L\cf4 , \cf6 3L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "Signature"\cf4 , \cf7 "MD5withRSA"\cf4 , \cf5 var11\cf4 , \cf5 s(\cf7 "1.2.840.113549.1.1.4"\cf4 , \cf7 "OID.1.2.840.113549.1.1.4"\cf5 )\cf4 , \cf5 m(\cf6 5L\cf4 , \cf6 1L\cf4 , \cf6 3L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "Signature"\cf4 , \cf7 "SHA1withRSA"\cf4 , \cf5 var11\cf4 , \cf5 s(\cf7 "1.2.840.113549.1.1.5"\cf4 , \cf7 "OID.1.2.840.113549.1.1.5"\cf4 , \cf7 "1.3.14.3.2.29"\cf5 )\cf4 , \cf5 m(\cf6 6L\cf4 , \cf6 1L\cf4 , \cf6 3L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "Signature"\cf4 , \cf7 "SHA224withRSA"\cf4 , \cf5 var11\cf4 , \cf5 s(\cf7 "1.2.840.113549.1.1.14"\cf4 , \cf7 "OID.1.2.840.113549.1.1.14"\cf5 )\cf4 , \cf5 m(\cf6 70L\cf4 , \cf6 1L\cf4 , \cf6 3L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "Signature"\cf4 , \cf7 "SHA256withRSA"\cf4 , \cf5 var11\cf4 , \cf5 s(\cf7 "1.2.840.113549.1.1.11"\cf4 , \cf7 "OID.1.2.840.113549.1.1.11"\cf5 )\cf4 , \cf5 m(\cf6 64L\cf4 , \cf6 1L\cf4 , \cf6 3L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "Signature"\cf4 , \cf7 "SHA384withRSA"\cf4 , \cf5 var11\cf4 , \cf5 s(\cf7 "1.2.840.113549.1.1.12"\cf4 , \cf7 "OID.1.2.840.113549.1.1.12"\cf5 )\cf4 , \cf5 m(\cf6 65L\cf4 , \cf6 1L\cf4 , \cf6 3L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "Signature"\cf4 , \cf7 "SHA512withRSA"\cf4 , \cf5 var11\cf4 , \cf5 s(\cf7 "1.2.840.113549.1.1.13"\cf4 , \cf7 "OID.1.2.840.113549.1.1.13"\cf5 )\cf4 , \cf5 m(\cf6 66L\cf4 , \cf6 1L\cf4 , \cf6 3L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "KeyGenerator"\cf4 , \cf7 "SunTlsRsaPremasterSecret"\cf4 , \cf7 "sun.security.pkcs11.P11TlsRsaPremasterSecretGenerator"\cf4 , \cf5 m(\cf6 880L\cf4 , \cf6 884L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "KeyGenerator"\cf4 , \cf7 "SunTlsMasterSecret"\cf4 , \cf7 "sun.security.pkcs11.P11TlsMasterSecretGenerator"\cf4 , \cf5 m(\cf6 881L\cf4 , \cf6 885L\cf4 , \cf6 883L\cf4 , \cf6 887L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "KeyGenerator"\cf4 , \cf7 "SunTlsKeyMaterial"\cf4 , \cf7 "sun.security.pkcs11.P11TlsKeyMaterialGenerator"\cf4 , \cf5 m(\cf6 882L\cf4 , \cf6 886L\cf5 ))\cf4 ;\
        \cf5 d(\cf7 "KeyGenerator"\cf4 , \cf7 "SunTlsPrf"\cf4 , \cf7 "sun.security.pkcs11.P11TlsPrfGenerator"\cf4 , \cf5 m(\cf6 888L\cf4 , \cf6 2147484531L\cf5 ))\cf4 ;\
    \cf5 \}\
\
    \cf4 private static class \cf5 SunPKCS11Rep \cf4 implements \cf5 Serializable \{\
        \cf4 static final long \cf5 serialVersionUID = -\cf6 2896606995897745419L\cf4 ;\
        private final \cf5 String providerName\cf4 ;\
        private final \cf5 String configName\cf4 ;\
\
        \cf5 SunPKCS11Rep(SunPKCS11 var1) \cf4 throws \cf5 NotSerializableException \{\
            \cf4 this\cf5 .providerName = var1.getName()\cf4 ;\
            this\cf5 .configName = var1.configName\cf4 ;\
            if \cf5 (Security.getProvider(\cf4 this\cf5 .providerName) != var1) \{\
                \cf4 throw new \cf5 NotSerializableException(\cf7 "Only SunPKCS11 providers installed in java.security.Security can be serialized"\cf5 )\cf4 ;\
            \cf5 \}\
        \}\
\
        \cf4 private \cf5 Object readResolve() \cf4 throws \cf5 ObjectStreamException \{\
            SunPKCS11 var1 = (SunPKCS11)Security.getProvider(\cf4 this\cf5 .providerName)\cf4 ;\
            if \cf5 (var1 != \cf4 null \cf5 && var1.configName.equals(\cf4 this\cf5 .configName)) \{\
                \cf4 return \cf5 var1\cf4 ;\
            \cf5 \} \cf4 else \cf5 \{\
                \cf4 throw new \cf5 NotSerializableException(\cf7 "Could not find " \cf5 + \cf4 this\cf5 .providerName + \cf7 " in installed providers"\cf5 )\cf4 ;\
            \cf5 \}\
        \}\
    \}\
\
    \cf4 private static final class \cf5 P11Service \cf4 extends \cf5 Service \{\
        \cf4 private final \cf5 Token token\cf4 ;\
        private final long \cf5 mechanism\cf4 ;\
\
        \cf5 P11Service(Token var1\cf4 , \cf5 String var2\cf4 , \cf5 String var3\cf4 , \cf5 String var4\cf4 , \cf5 String[] var5\cf4 , long \cf5 var6) \{\
            \cf4 super\cf5 (var1.provider\cf4 , \cf5 var2\cf4 , \cf5 var3\cf4 , \cf5 var4\cf4 , \cf5 toList(var5)\cf4 , \cf5 (Map)\cf4 null\cf5 )\cf4 ;\
            this\cf5 .token = var1\cf4 ;\
            this\cf5 .mechanism = var6 & \cf6 4294967295L\cf4 ;\
        \cf5 \}\
\
        \cf4 private static \cf5 List<String> toList(String[] var0) \{\
            \cf4 return \cf5 var0 == \cf4 null \cf5 ? \cf4 null \cf5 : Arrays.asList(var0)\cf4 ;\
        \cf5 \}\
\
        \cf4 public \cf5 Object newInstance(Object var1) \cf4 throws \cf5 NoSuchAlgorithmException \{\
            \cf4 if \cf5 (!\cf4 this\cf5 .token.isValid()) \{\
                \cf4 throw new \cf5 NoSuchAlgorithmException(\cf7 "Token has been removed"\cf5 )\cf4 ;\
            \cf5 \} \cf4 else \cf5 \{\
                \cf4 try \cf5 \{\
                    \cf4 return this\cf5 .newInstance0(var1)\cf4 ;\
                \cf5 \} \cf4 catch \cf5 (PKCS11Exception var3) \{\
                    \cf4 throw new \cf5 NoSuchAlgorithmException(var3)\cf4 ;\
                \cf5 \}\
            \}\
        \}\
\
        \cf4 public \cf5 Object newInstance0(Object var1) \cf4 throws \cf5 PKCS11Exception\cf4 , \cf5 NoSuchAlgorithmException \{\
            String var2 = \cf4 this\cf5 .getAlgorithm()\cf4 ;\
            \cf5 String var3 = \cf4 this\cf5 .getType()\cf4 ;\
            if \cf5 (var3 == \cf7 "MessageDigest"\cf5 ) \{\
                \cf4 return new \cf5 P11Digest(\cf4 this\cf5 .token\cf4 , \cf5 var2\cf4 , this\cf5 .mechanism)\cf4 ;\
            \cf5 \} \cf4 else if \cf5 (var3 == \cf7 "Cipher"\cf5 ) \{\
                \cf4 return \cf5 var2.startsWith(\cf7 "RSA"\cf5 ) ? \cf4 new \cf5 P11RSACipher(\cf4 this\cf5 .token\cf4 , \cf5 var2\cf4 , this\cf5 .mechanism) : \cf4 new \cf5 P11Cipher(\cf4 this\cf5 .token\cf4 , \cf5 var2\cf4 , this\cf5 .mechanism)\cf4 ;\
            \cf5 \} \cf4 else if \cf5 (var3 == \cf7 "Signature"\cf5 ) \{\
                \cf4 return new \cf5 P11Signature(\cf4 this\cf5 .token\cf4 , \cf5 var2\cf4 , this\cf5 .mechanism)\cf4 ;\
            \cf5 \} \cf4 else if \cf5 (var3 == \cf7 "Mac"\cf5 ) \{\
                \cf4 return new \cf5 P11Mac(\cf4 this\cf5 .token\cf4 , \cf5 var2\cf4 , this\cf5 .mechanism)\cf4 ;\
            \cf5 \} \cf4 else if \cf5 (var3 == \cf7 "KeyPairGenerator"\cf5 ) \{\
                \cf4 return new \cf5 P11KeyPairGenerator(\cf4 this\cf5 .token\cf4 , \cf5 var2\cf4 , this\cf5 .mechanism)\cf4 ;\
            \cf5 \} \cf4 else if \cf5 (var3 == \cf7 "KeyAgreement"\cf5 ) \{\
                \cf4 return \cf5 var2.equals(\cf7 "ECDH"\cf5 ) ? \cf4 new \cf5 P11ECDHKeyAgreement(\cf4 this\cf5 .token\cf4 , \cf5 var2\cf4 , this\cf5 .mechanism) : \cf4 new \cf5 P11KeyAgreement(\cf4 this\cf5 .token\cf4 , \cf5 var2\cf4 , this\cf5 .mechanism)\cf4 ;\
            \cf5 \} \cf4 else if \cf5 (var3 == \cf7 "KeyFactory"\cf5 ) \{\
                \cf4 return this\cf5 .token.getKeyFactory(var2)\cf4 ;\
            \cf5 \} \cf4 else if \cf5 (var3 == \cf7 "SecretKeyFactory"\cf5 ) \{\
                \cf4 return new \cf5 P11SecretKeyFactory(\cf4 this\cf5 .token\cf4 , \cf5 var2)\cf4 ;\
            \cf5 \} \cf4 else if \cf5 (var3 == \cf7 "KeyGenerator"\cf5 ) \{\
                \cf4 if \cf5 (var2 == \cf7 "SunTlsRsaPremasterSecret"\cf5 ) \{\
                    \cf4 return new \cf5 P11TlsRsaPremasterSecretGenerator(\cf4 this\cf5 .token\cf4 , \cf5 var2\cf4 , this\cf5 .mechanism)\cf4 ;\
                \cf5 \} \cf4 else if \cf5 (var2 == \cf7 "SunTlsMasterSecret"\cf5 ) \{\
                    \cf4 return new \cf5 P11TlsMasterSecretGenerator(\cf4 this\cf5 .token\cf4 , \cf5 var2\cf4 , this\cf5 .mechanism)\cf4 ;\
                \cf5 \} \cf4 else if \cf5 (var2 == \cf7 "SunTlsKeyMaterial"\cf5 ) \{\
                    \cf4 return new \cf5 P11TlsKeyMaterialGenerator(\cf4 this\cf5 .token\cf4 , \cf5 var2\cf4 , this\cf5 .mechanism)\cf4 ;\
                \cf5 \} \cf4 else \cf5 \{\
                    \cf4 return \cf5 var2 == \cf7 "SunTlsPrf" \cf5 ? \cf4 new \cf5 P11TlsPrfGenerator(\cf4 this\cf5 .token\cf4 , \cf5 var2\cf4 , this\cf5 .mechanism) : \cf4 new \cf5 P11KeyGenerator(\cf4 this\cf5 .token\cf4 , \cf5 var2\cf4 , this\cf5 .mechanism)\cf4 ;\
                \cf5 \}\
            \} \cf4 else if \cf5 (var3 == \cf7 "SecureRandom"\cf5 ) \{\
                \cf4 return this\cf5 .token.getRandom()\cf4 ;\
            \cf5 \} \cf4 else if \cf5 (var3 == \cf7 "KeyStore"\cf5 ) \{\
                \cf4 return this\cf5 .token.getKeyStore()\cf4 ;\
            \cf5 \} \cf4 else if \cf5 (var3 == \cf7 "AlgorithmParameters"\cf5 ) \{\
                \cf4 return new \cf5 ECParameters()\cf4 ;\
            \cf5 \} \cf4 else \cf5 \{\
                \cf4 throw new \cf5 NoSuchAlgorithmException(\cf7 "Unknown type: " \cf5 + var3)\cf4 ;\
            \cf5 \}\
        \}\
\
        \cf4 public boolean \cf5 supportsParameter(Object var1) \{\
            \cf4 if \cf5 (var1 != \cf4 null \cf5 && \cf4 this\cf5 .token.isValid()) \{\
                \cf4 if \cf5 (!(var1 \cf4 instanceof \cf5 Key)) \{\
                    \cf4 throw new \cf5 InvalidParameterException(\cf7 "Parameter must be a Key"\cf5 )\cf4 ;\
                \cf5 \} \cf4 else \cf5 \{\
                    String var2 = \cf4 this\cf5 .getAlgorithm()\cf4 ;\
                    \cf5 String var3 = \cf4 this\cf5 .getType()\cf4 ;\
                    \cf5 Key var4 = (Key)var1\cf4 ;\
                    \cf5 String var5 = var4.getAlgorithm()\cf4 ;\
                    if \cf5 (var3 == \cf7 "Cipher" \cf5 && var2.startsWith(\cf7 "RSA"\cf5 ) || var3 == \cf7 "Signature" \cf5 && var2.endsWith(\cf7 "RSA"\cf5 )) \{\
                        \cf4 if \cf5 (!var5.equals(\cf7 "RSA"\cf5 )) \{\
                            \cf4 return false;\
                        \cf5 \} \cf4 else \cf5 \{\
                            \cf4 return this\cf5 .isLocalKey(var4) || var4 \cf4 instanceof \cf5 RSAPrivateKey || var4 \cf4 instanceof \cf5 RSAPublicKey\cf4 ;\
                        \cf5 \}\
                    \} \cf4 else if \cf5 (var3 == \cf7 "KeyAgreement" \cf5 && var2.equals(\cf7 "ECDH"\cf5 ) || var3 == \cf7 "Signature" \cf5 && var2.endsWith(\cf7 "ECDSA"\cf5 )) \{\
                        \cf4 if \cf5 (!var5.equals(\cf7 "EC"\cf5 )) \{\
                            \cf4 return false;\
                        \cf5 \} \cf4 else \cf5 \{\
                            \cf4 return this\cf5 .isLocalKey(var4) || var4 \cf4 instanceof \cf5 ECPrivateKey || var4 \cf4 instanceof \cf5 ECPublicKey\cf4 ;\
                        \cf5 \}\
                    \} \cf4 else if \cf5 (var3 == \cf7 "Signature" \cf5 && var2.endsWith(\cf7 "DSA"\cf5 )) \{\
                        \cf4 if \cf5 (!var5.equals(\cf7 "DSA"\cf5 )) \{\
                            \cf4 return false;\
                        \cf5 \} \cf4 else \cf5 \{\
                            \cf4 return this\cf5 .isLocalKey(var4) || var4 \cf4 instanceof \cf5 DSAPrivateKey || var4 \cf4 instanceof \cf5 DSAPublicKey\cf4 ;\
                        \cf5 \}\
                    \} \cf4 else if \cf5 (var3 != \cf7 "Cipher" \cf5 && var3 != \cf7 "Mac"\cf5 ) \{\
                        \cf4 if \cf5 (var3 == \cf7 "KeyAgreement"\cf5 ) \{\
                            \cf4 if \cf5 (!var5.equals(\cf7 "DH"\cf5 )) \{\
                                \cf4 return false;\
                            \cf5 \} \cf4 else \cf5 \{\
                                \cf4 return this\cf5 .isLocalKey(var4) || var4 \cf4 instanceof \cf5 DHPrivateKey || var4 \cf4 instanceof \cf5 DHPublicKey\cf4 ;\
                            \cf5 \}\
                        \} \cf4 else \cf5 \{\
                            \cf4 throw new \cf5 AssertionError(\cf7 "SunPKCS11 error: " \cf5 + var3 + \cf7 ", " \cf5 + var2)\cf4 ;\
                        \cf5 \}\
                    \} \cf4 else \cf5 \{\
                        \cf4 return this\cf5 .isLocalKey(var4) || \cf7 "RAW"\cf5 .equals(var4.getFormat())\cf4 ;\
                    \cf5 \}\
                \}\
            \} \cf4 else \cf5 \{\
                \cf4 return false;\
            \cf5 \}\
        \}\
\
        \cf4 private boolean \cf5 isLocalKey(Key var1) \{\
            \cf4 return \cf5 var1 \cf4 instanceof \cf5 P11Key && ((P11Key)var1).token == \cf4 this\cf5 .token\cf4 ;\
        \cf5 \}\
\
        \cf4 public \cf5 String toString() \{\
            \cf4 return super\cf5 .toString() + \cf7 " (" \cf5 + Functions.getMechanismName(\cf4 this\cf5 .mechanism) + \cf7 ")"\cf4 ;\
        \cf5 \}\
    \}\
\
    \cf4 private static class \cf5 TokenPoller \cf4 implements \cf5 Runnable \{\
        \cf4 private final \cf5 SunPKCS11 provider\cf4 ;\
        private volatile boolean \cf5 enabled\cf4 ;\
\
        private \cf5 TokenPoller(SunPKCS11 var1) \{\
            \cf4 this\cf5 .provider = var1\cf4 ;\
            this\cf5 .enabled = \cf4 true;\
        \cf5 \}\
\
        \cf4 public void \cf5 run() \{\
            \cf4 int \cf5 var1 = \cf4 this\cf5 .provider.config.getInsertionCheckInterval()\cf4 ;\
\
            while\cf5 (\cf4 this\cf5 .enabled) \{\
                \cf4 try \cf5 \{\
                    Thread.sleep((\cf4 long\cf5 )var1)\cf4 ;\
                \cf5 \} \cf4 catch \cf5 (InterruptedException var4) \{\
                    \cf4 break;\
                \cf5 \}\
\
                \cf4 if \cf5 (!\cf4 this\cf5 .enabled) \{\
                    \cf4 break;\
                \cf5 \}\
\
                \cf4 try \cf5 \{\
                    \cf4 this\cf5 .provider.initToken((CK_SLOT_INFO)\cf4 null\cf5 )\cf4 ;\
                \cf5 \} \cf4 catch \cf5 (PKCS11Exception var3) \{\
                    \cf4 ;\
                \cf5 \}\
            \}\
\
        \}\
\
        \cf4 void \cf5 disable() \{\
            \cf4 this\cf5 .enabled = \cf4 false;\
        \cf5 \}\
    \}\
\
    \cf4 private static final class \cf5 Descriptor \{\
        \cf4 final \cf5 String type\cf4 ;\
        final \cf5 String algorithm\cf4 ;\
        final \cf5 String className\cf4 ;\
        final \cf5 String[] aliases\cf4 ;\
        final int\cf5 [] mechanisms\cf4 ;\
\
        private \cf5 Descriptor(String var1\cf4 , \cf5 String var2\cf4 , \cf5 String var3\cf4 , \cf5 String[] var4\cf4 , int\cf5 [] var5) \{\
            \cf4 this\cf5 .type = var1\cf4 ;\
            this\cf5 .algorithm = var2\cf4 ;\
            this\cf5 .className = var3\cf4 ;\
            this\cf5 .aliases = var4\cf4 ;\
            this\cf5 .mechanisms = var5\cf4 ;\
        \cf5 \}\
\
        \cf4 private \cf5 SunPKCS11.P11Service service(Token var1\cf4 , int \cf5 var2) \{\
            \cf4 return new \cf5 SunPKCS11.P11Service(var1\cf4 , this\cf5 .type\cf4 , this\cf5 .algorithm\cf4 , this\cf5 .className\cf4 , this\cf5 .aliases\cf4 , \cf5 (\cf4 long\cf5 )var2)\cf4 ;\
        \cf5 \}\
\
        \cf4 public \cf5 String toString() \{\
            \cf4 return this\cf5 .type + \cf7 "." \cf5 + \cf4 this\cf5 .algorithm\cf4 ;\
        \cf5 \}\
    \}\
\}\
\
}