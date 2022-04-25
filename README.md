# JV-Product-Card

Éste es un paquete de pruebas de despligues a NPM

### Joel Vargas

### Ejemplo

```
import { ProductCard, ProductImage, ProductTitle, ProductButtons } from 'jv-product-card';

```

```
<ProductCard
product={product}
initialValues={{
          count: 4,
          maxCount: 10,
        }} >
{({ reset, count, isMaxCountReached, maxCount, increaseBy }) => (
<>
<ProductImage />
<ProductTitle />
<ProductButtons />
</>
)}
</ProductCard>
```
