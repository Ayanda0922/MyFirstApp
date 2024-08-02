# 
import { StatusBar } from 'expo-status-bar';
import { FlatList, StyleSheet, Text, View } from 'react-native';

export default function App() {

  return (

<View style={styles.ViewStyle}>
    
      <Text style={styles.headingText}>MyToDoList</Text>
     
      <Text style={styles.subheadingText}>1.Bathing</Text>
      <Text style={styles.secondsubheadingText}>2.Gym</Text> 
      <Text style={styles.thirdsubheadingText}>3.cooking</Text>
      <Text style={styles.fourthsubheadingText}>4.Hockey</Text>
      <Text style={styles.fifthsubheadingText}>5.Watching movies</Text>
      <Text style={styles.sixthsubheadingText}>6.TikTok</Text>
      <Text style={styles.seventhsubheadingText}>7.Sleeping</Text>

    </View>
  );
}

const styles = StyleSheet.create({
  ViewStyle: {
    flex: 1,
    backgroundColor: '#fff',
    alignItems: 'center',
    justifyContent: 'center',
  }, 
  headingText: { 
    fontSize: 40, 
    color: "black",
    fontWeight: "bold"
  },
  
  subheadingText:{
    fontSize: 40,
    color: "black", 
    fontWeight: "normal"
 
  },
  secondsubheadingText: {
    fontSize: 40, 
    color: "black",
    fontWeight: "normal"
  },
  thirdsubheadingText: {
    fontSize: 40,
    color: "black",
    fontWeight: "normal"
  },
fourthsubheadingText: { 
  fontSize: 40,
  color: "black",
  fontWeight: "normal"
},
fifthsubheadingText: {
  fontSize: 40 ,
  color: "black",
  fontWeight: "normal"
},
sixthsubheadingText: {
  fontSize: 40,
  color: "black",
  fontWeight: "normal"
},
seventhsubheadingText: {
  fontSize: 40,
  color: "black",
  fontWeight: "normal"
}




}

});
export default App;

