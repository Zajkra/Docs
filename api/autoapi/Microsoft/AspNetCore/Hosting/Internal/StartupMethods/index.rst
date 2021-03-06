

StartupMethods Class
====================





Namespace
    :dn:ns:`Microsoft.AspNetCore.Hosting.Internal`
Assemblies
    * Microsoft.AspNetCore.Hosting

----

.. contents::
   :local:



Inheritance Hierarchy
---------------------


* :dn:cls:`System.Object`
* :dn:cls:`Microsoft.AspNetCore.Hosting.Internal.StartupMethods`








Syntax
------

.. code-block:: csharp

    public class StartupMethods








.. dn:class:: Microsoft.AspNetCore.Hosting.Internal.StartupMethods
    :hidden:

.. dn:class:: Microsoft.AspNetCore.Hosting.Internal.StartupMethods

Constructors
------------

.. dn:class:: Microsoft.AspNetCore.Hosting.Internal.StartupMethods
    :noindex:
    :hidden:

    
    .. dn:constructor:: Microsoft.AspNetCore.Hosting.Internal.StartupMethods.StartupMethods(System.Action<Microsoft.AspNetCore.Builder.IApplicationBuilder>)
    
        
    
        
        :type configure: System.Action<System.Action`1>{Microsoft.AspNetCore.Builder.IApplicationBuilder<Microsoft.AspNetCore.Builder.IApplicationBuilder>}
    
        
        .. code-block:: csharp
    
            public StartupMethods(Action<IApplicationBuilder> configure)
    
    .. dn:constructor:: Microsoft.AspNetCore.Hosting.Internal.StartupMethods.StartupMethods(System.Action<Microsoft.AspNetCore.Builder.IApplicationBuilder>, System.Func<Microsoft.Extensions.DependencyInjection.IServiceCollection, System.IServiceProvider>)
    
        
    
        
        :type configure: System.Action<System.Action`1>{Microsoft.AspNetCore.Builder.IApplicationBuilder<Microsoft.AspNetCore.Builder.IApplicationBuilder>}
    
        
        :type configureServices: System.Func<System.Func`2>{Microsoft.Extensions.DependencyInjection.IServiceCollection<Microsoft.Extensions.DependencyInjection.IServiceCollection>, System.IServiceProvider<System.IServiceProvider>}
    
        
        .. code-block:: csharp
    
            public StartupMethods(Action<IApplicationBuilder> configure, Func<IServiceCollection, IServiceProvider> configureServices)
    

Properties
----------

.. dn:class:: Microsoft.AspNetCore.Hosting.Internal.StartupMethods
    :noindex:
    :hidden:

    
    .. dn:property:: Microsoft.AspNetCore.Hosting.Internal.StartupMethods.ConfigureDelegate
    
        
        :rtype: System.Action<System.Action`1>{Microsoft.AspNetCore.Builder.IApplicationBuilder<Microsoft.AspNetCore.Builder.IApplicationBuilder>}
    
        
        .. code-block:: csharp
    
            public Action<IApplicationBuilder> ConfigureDelegate { get; }
    
    .. dn:property:: Microsoft.AspNetCore.Hosting.Internal.StartupMethods.ConfigureServicesDelegate
    
        
        :rtype: System.Func<System.Func`2>{Microsoft.Extensions.DependencyInjection.IServiceCollection<Microsoft.Extensions.DependencyInjection.IServiceCollection>, System.IServiceProvider<System.IServiceProvider>}
    
        
        .. code-block:: csharp
    
            public Func<IServiceCollection, IServiceProvider> ConfigureServicesDelegate { get; }
    

