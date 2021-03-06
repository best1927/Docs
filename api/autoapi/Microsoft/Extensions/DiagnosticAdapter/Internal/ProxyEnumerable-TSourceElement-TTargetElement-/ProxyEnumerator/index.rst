

ProxyEnumerator Class
=====================





Namespace
    :dn:ns:`Microsoft.Extensions.DiagnosticAdapter.Internal.ProxyEnumerable`2`
Assemblies
    * Microsoft.Extensions.DiagnosticAdapter

----

.. contents::
   :local:



Inheritance Hierarchy
---------------------


* :dn:cls:`System.Object`
* :dn:cls:`Microsoft.Extensions.DiagnosticAdapter.Internal.ProxyEnumerable\<TSourceElement, TTargetElement>.ProxyEnumerator`








Syntax
------

.. code-block:: csharp

    public class ProxyEnumerator : IEnumerator<TTargetElement>, IEnumerator, IDisposable








.. dn:class:: Microsoft.Extensions.DiagnosticAdapter.Internal.ProxyEnumerable`2.ProxyEnumerator
    :hidden:

.. dn:class:: Microsoft.Extensions.DiagnosticAdapter.Internal.ProxyEnumerable<TSourceElement, TTargetElement>.ProxyEnumerator

Constructors
------------

.. dn:class:: Microsoft.Extensions.DiagnosticAdapter.Internal.ProxyEnumerable<TSourceElement, TTargetElement>.ProxyEnumerator
    :noindex:
    :hidden:

    
    .. dn:constructor:: Microsoft.Extensions.DiagnosticAdapter.Internal.ProxyEnumerable<TSourceElement, TTargetElement>.ProxyEnumerator.ProxyEnumerator(System.Collections.Generic.IEnumerator<TSourceElement>, System.Type)
    
        
    
        
        :type source: System.Collections.Generic.IEnumerator<System.Collections.Generic.IEnumerator`1>{TSourceElement}
    
        
        :type proxyType: System.Type
    
        
        .. code-block:: csharp
    
            public ProxyEnumerator(IEnumerator<TSourceElement> source, Type proxyType)
    

Properties
----------

.. dn:class:: Microsoft.Extensions.DiagnosticAdapter.Internal.ProxyEnumerable<TSourceElement, TTargetElement>.ProxyEnumerator
    :noindex:
    :hidden:

    
    .. dn:property:: Microsoft.Extensions.DiagnosticAdapter.Internal.ProxyEnumerable<TSourceElement, TTargetElement>.ProxyEnumerator.Current
    
        
        :rtype: TTargetElement
    
        
        .. code-block:: csharp
    
            public TTargetElement Current { get; }
    
    .. dn:property:: Microsoft.Extensions.DiagnosticAdapter.Internal.ProxyEnumerable<TSourceElement, TTargetElement>.ProxyEnumerator.System.Collections.IEnumerator.Current
    
        
        :rtype: System.Object
    
        
        .. code-block:: csharp
    
            object IEnumerator.Current { get; }
    

Methods
-------

.. dn:class:: Microsoft.Extensions.DiagnosticAdapter.Internal.ProxyEnumerable<TSourceElement, TTargetElement>.ProxyEnumerator
    :noindex:
    :hidden:

    
    .. dn:method:: Microsoft.Extensions.DiagnosticAdapter.Internal.ProxyEnumerable<TSourceElement, TTargetElement>.ProxyEnumerator.Dispose()
    
        
    
        
        .. code-block:: csharp
    
            public void Dispose()
    
    .. dn:method:: Microsoft.Extensions.DiagnosticAdapter.Internal.ProxyEnumerable<TSourceElement, TTargetElement>.ProxyEnumerator.MoveNext()
    
        
        :rtype: System.Boolean
    
        
        .. code-block:: csharp
    
            public bool MoveNext()
    
    .. dn:method:: Microsoft.Extensions.DiagnosticAdapter.Internal.ProxyEnumerable<TSourceElement, TTargetElement>.ProxyEnumerator.Reset()
    
        
    
        
        .. code-block:: csharp
    
            public void Reset()
    

