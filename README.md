# HortiFácil App

This project is a fresh produce mobile app developed with React Native + Expo. Below are the main components used.

## React Native Components
SafeAreaView (react-native-safe-area-context): Safe area support for iOS/Android.
View: Generic layout container.
Text: Text display.
TextInput: Text input fields (email, password, address, etc.).
TouchableOpacity: Buttons and clickable areas.
Image: Image display (logos, products, placeholders).
FlatList: Efficient item listing (stores, products, addresses, cart).
ScrollView: Vertical scrolling for screens such as Profile.
Switch: Toggle state (e.g. address without number).
Alert: Display alerts/confirmation and error modals.

## Navigation Components
NavigationContainer (@react-navigation/native): Navigation container.
createNativeStackNavigator (@react-navigation/native-stack): Screen stack (Login, Signup, Store, etc.).
createBottomTabNavigator (@react-navigation/bottom-tabs): Main tabs (Stores, Cart, Profile).

## React Hooks
useState: Local state inside components.
useContext: Consumes the cart context.
createContext: Creates the CartContext.
useMemo: Memoizes the filtered product list.

## tate Management
CartContext: Custom context used to manage cart items, delivery policies, and add/remove products.
## Extra Libraries
@expo/vector-icons: Icons (Feather, FontAwesome, MaterialCommunityIcons).
react-native-qrcode-svg: QR code generation for Pix payments.
---

   ## Integrantes
   Felipe Olimpio Fonseca.

### Como rodar

```bash
npm install
npx expo start
```

> Certifique-se de ter o Expo Go instalado no seu dispositivo para testes em mobile.
