# NM-Product-Card

Este es un paquete de pruebas de despliegue en NPM

### Nico Marino

## Ejemplo 
```
import {ProductCard, ProductImage, ProductTitle, ProductButtons} from 'nm-product-card';
```

```
<ProductCard 
                product={product} 
                initialValues={{
                    count: 6, 
                    // maxCount: 10,
                  }}
>
    {
    ({reset, increaseBy, isMaxCountReached, count, maxCount }) => (
      
          <>
            <ProductImage/>
            <ProductTitle/>
            <ProductButtons/>
          </>
        )                  
    }             
</ProductCard>
```